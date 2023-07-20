<template>
	<div class="flex flex-row">
	<nav class="w-64 h-screen fixed bg-zinc-900">
		<div class="px-4 pt-8 pb-4">
			<h1 class="text-white font-extrabold font-mono text-3xl">Wisemad</h1>
		</div>
		<div class="px-4 pt-4 pb-6">
			<ul class="flex flex-col gap-3.5">
				<li class="">
					<RouterLink to="/feed" class="flex text-sm text-white font-bold opacity-80 hover:opacity-100">
                        <svg class="mr-3 fill-white" role="img" height="24" width="24" viewBox="0 0 24 24">
                            <path
                                d="M13.5 1.515a3 3 0 00-3 0L3 5.845a2 2 0 00-1 1.732V21a1 1 0 001 1h6a1 1 0 001-1v-6h4v6a1 1 0 001 1h6a1 1 0 001-1V7.577a2 2 0 00-1-1.732l-7.5-4.33z">
                            </path>
                        </svg>
                        Inicio
					</RouterLink>
				</li>
				<li class="">
					<RouterLink to="/profile/" class="flex text-sm text-white font-bold opacity-80 hover:opacity-100">
                        <svg class="mr-3" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
							<path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path>
							<circle cx="12" cy="7" r="4"></circle>
						</svg>
						Perfil
					</RouterLink>
				</li>
				<li class="">
					<RouterLink to="/search" class="flex text-sm text-white font-bold opacity-80 hover:opacity-100">
                        <svg class="mr-3 fill-white" role="img" height="24" width="24" viewBox="0 0 24 24">
                            <path
                                d="M10.533 1.279c-5.18 0-9.407 4.14-9.407 9.279s4.226 9.279 9.407 9.279c2.234 0 4.29-.77 5.907-2.058l4.353 4.353a1 1 0 101.414-1.414l-4.344-4.344a9.157 9.157 0 002.077-5.816c0-5.14-4.226-9.28-9.407-9.28zm-7.407 9.279c0-4.006 3.302-7.28 7.407-7.28s7.407 3.274 7.407 7.28-3.302 7.279-7.407 7.279-7.407-3.273-7.407-7.28z">
                            </path>
                        </svg> 
                        Buscar
					</RouterLink>
				</li>
			</ul>
		</div>
		<div class="px-4 pb-4">
			<button id="popup-trigger-btn" class="flex gap-3 opacity-80 hover:opacity-100 transition-opacity">
            	<div class="w-6 h-6 rounded-sm bg-gray-100 flex items-center justify-center">
					<svg class="fill-zinc-800" role="img" height="12" width="12" aria-hidden="true" viewBox="0 0 16 16">
						<path
						d="M15.25 8a.75.75 0 01-.75.75H8.75v5.75a.75.75 0 01-1.5 0V8.75H1.5a.75.75 0 010-1.5h5.75V1.5a.75.75 0 011.5 0v5.75h5.75a.75.75 0 01.75.75z">
						</path>
					</svg>
				</div>
				<div class="text-white text-sm font-bold self-center">Gerar plano de estudos</div>
            </button>
			<div class="mt-3.5 mb-3 bg-zinc-800 w-10 h-1"></div>
			<ul class="opacity-90 hover:opacity-100">
				<li class="text-white text-sm">
					<a href="#">Plano de Estudos 1 | 83%</a>
				</li>
			</ul>
		</div>
	</nav>
	<main class="flex-1 ml-64 ">
		<header class="flex flex-row sticky justify-between h-30 w-full pl-4 pr-4 py-4 bg-zinc-900">
			<div class="flex flex-row gap-3">
				<svg class="cursor-pointer" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 18l-6-6 6-6"/></svg>
				<svg class="cursor-pointer" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 18l6-6-6-6"/></svg>
			</div>
			<button class="flex flex-row gap-1.5 opacity-80 hover:opacity-100">
				<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5.52 19c.64-2.2 1.84-3 3.22-3h6.52c1.38 0 2.58.8 3.22 3"/><circle cx="12" cy="10" r="3"/><circle cx="12" cy="12" r="10"/></svg>
				<p class="text-white">leto-corcrop</p>
			</button>
		</header>
		<RouterView />
	</main>
	</div>
</template>