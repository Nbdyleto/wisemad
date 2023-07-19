<template>
    <!-- Phrases and Challenges Section -->
    <section>
        <div class="flex flex-row px-8 py-4">
            <!-- Quotes Card -->
            <div class="flex-row w-1/2 h-1/2 font-mono">
                <div class="m-4 text-lg font-semibold text-gray-800">Inspire-se, e...</div>
                <div class="rounded-lg border-2 border-zinc-300 shadow-xl bg-zinc-200 overflow-hidden cursor-pointer group">
                    <div class="m-4">
                        <div class="pt-12">
                            <p class="text-gray-800 font-semibold font-mono text-xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                            <a href="#" class="text-lg font-semibold text-zinc-500">@pussycat</a> <span class="text-2xl font-mono">-</span>
                        </div>
                    </div>
                    <div class="flex flex-grow items-end">
                        <div class="h-40 flex-grow bg-emerald-500">
                            <img src="{% static 'profile/profile-16.png' %}" alt="Autor Image" class="gray-image-primary w-full h-full rounded-lg object-cover">
                        </div>
                    </div>
                </div>
            </div>
            <!-- Challenges Card -->
            <div class="flex-row w-full font-mono">
                <div class="m-4 text-lg font-semibold text-gray-800">Desafie-se.</div>
                <div class="flex flex-row gap-4 items-center rounded-lg border-2 border-zinc-300 shadow-lg duration-300 bg-zinc-200 m-4 p-4 cursor-pointer hover:shadow-zinc-300">
                    <div>
                        <div class="w-24 h-24 bg-rose-500 rounded-full">
                            <img src="{% static 'profile/profile-17.png' %}" alt="Challenge Badge" class="gray-image-primary w-full h-full border-2 border-zinc-300 rounded-full object-cover">
                        </div>
                    </div>
                    <div>
                        <p class="text-lg font-bold text-gray-800">Challenge 1</p>
                        <p class="text-zinc-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum consequat velit in rutrum aliquet.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Current Plans Section-->
    <section class="px-8 pt-6 pb-4">
        <div class="flex pb-4 ml-4">
            <span class="font-mono font-semibold text-lg text-gray-800">Continue de onde parou.</span>
        </div>
        <div class="flex">
            <div class="md:w-1/5 md:h-1/5 rounded overflow-hidden shadow-xl border border-zinc-300 bg-zinc-200 hover:shadow-zinc-400 ease-in duration-100 cursor-pointer group">
                <div class="w-full h-48">
                    <div class="bg-fuchsia-950/10 border-x-fuchsia-950 mb-[2.5px] pt-1 rounded-md">
                        <div class="h-2 rounded-md">
                            <div class="bg-rose-500 h-full rounded-md"></div>
                        </div>
                    </div>
                    <div class="relative w-full h-full overflow-hidden bg-fuchsia-900">
                        <img class="gray-image-primary absolute w-full h-full object-cover transition-all duration-300 transform group-hover:scale-110 hover:brightness-50 hover:saturate-150" src="">
                    </div>
                </div>
                <div class="px-4 py-6">
                    <div class="font-mono text-base text-gray-800 font-semibold">Syllabus Name</div>
                </div>            
            </div>
        </div>
    </section>
</template>