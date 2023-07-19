<template>
    <section>
        <div class="h-fit md:h-64 w-full bg-emerald-600 md:overflow-y-scroll shadow-md shadow-zinc-400">
            <img class="w-full opacity-80 saturate-200 grayscale brightness-75 object-cover" src="https://image3.cdn.seaart.ai/2023-06-27/38815254409285/f3d6f24afc77e0cbe5ed9805987fec1873f6394a.png">
        </div>
        <div class="absolute left-1/2 top-16 md:top-56">
            <div class="flex flex-col items-center justify-center">
                <!-- Profile Picture -->
                <div class="mb-4">
                    <div class="bg-emerald-500 border-4 border-white rounded-full">
                        <img class="w-36 h-36 opacity-80 saturate-200 grayscale brightness-125 rounded-full object-cover" src="https://image6.cdn.seaart.ai/2023-06-24/38074585178181/e9d190a126690de8aed5488d02035fc5297b205f.png">
                    </div>
                </div>
                <!-- Profile Info -->
                <div class="flex flex-col justify-center items-center gap-4 w-full">
                    <!-- Username -->
                    <div class="text-center">
                        <h3 class="text-2xl text-gray-700 font-bold leading-normal">@leto-corcrop</h3>
                        <div class="text-xs text-gray-400 font-bold uppercase">
                            <i class="fas fa-map-marker-alt text-gray-500 opacity-80"></i>Ávido por Coisas
                        </div>
                    </div>
                    <!-- Badges -->
                    <div class="flex flex-row flex-wrap max-w-[250px] md:max-w-xl gap-1">
                        <div class="w-10 h-10 rounded-full bg-emerald-400 shadow-md shadow-zinc-400 border border-white"></div>
                        <div class="w-10 h-10 rounded-full bg-emerald-400 shadow-md shadow-zinc-400 border border-white"></div>
                        <div class="w-10 h-10 rounded-full bg-emerald-400 shadow-md shadow-zinc-400 border border-white"></div>
                        <div class="w-10 h-10 rounded-full bg-emerald-400 shadow-md shadow-zinc-400 border border-white"></div>
                        <div class="w-10 h-10 rounded-full bg-emerald-400 shadow-md shadow-zinc-400 border border-white"></div>
                    </div>
                    <div class="w-12 h-0.5 mt-2 bg-gray-400"></div>
                    <div class="flex flex-row text-center gap-6">
                        <div class="flex flex-col">
                            <span class="text-xl font-bold block uppercase tracking-wide text-gray-700">5</span>
                            <span class="text-sm font-semibold text-gray-400">Planos</span>
                            <span class="text-sm font-semibold text-gray-400">Criados</span>
                        </div>
                        <div class="flex flex-col">
                            <span class="text-xl font-bold block uppercase tracking-wide text-gray-700">4</span>
                            <span class="text-sm font-semibold text-gray-400">Planos</span>
                            <span class="text-sm font-semibold text-gray-400">Finalizados</span>
                        </div>
                        <div class="flex flex-col">
                            <span class="text-xl font-bold block uppercase tracking-wide text-gray-700">12</span>
                            <span class="text-sm font-semibold text-gray-400">Desafios</span>
                            <span class="text-sm font-semibold text-gray-400">Finalizados</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
     </section>
</template>