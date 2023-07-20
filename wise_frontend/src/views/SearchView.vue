<script>
import SyllabusCard from '../components/SyllabusCard.vue';
import BadgeCard from '../components/BadgeCard.vue';
import ProfileCard from '../components/ProfileCard.vue';

export default {
    name: 'SearchView',
    components: {
        SyllabusCard,
        BadgeCard,
        ProfileCard,
    }
}
</script>

<template>
    <!-- Search bar-->
    <section class="">
        <div class="">
            <div class="p-4 flex space-x-4">  
                <input type="search" class="p-4 w-full bg-zinc-200 rounded-full" placeholder="O que você busca para estudar?">
                <a href="#" class="inline-block py-4 px-6 bg-gray-600 text-white rounded-full">Pesquisar</a>
            </div>
        </div>   
    </section>
    
    <!-- Recent Searchs -->
    <section class="p-4">
        <div class="flex flex-row justify-between mb-4">
            <p class="font-bold text-xl text-gray-800">Pesquisas recentes</p>
            <RouterLink to="recent-searches" class="font-semibold text-md text-gray-500">Ver todos</RouterLink>
        </div>
        <div class="items-start grid grid-cols-2 md:grid-cols-6 gap-2">
            <SyllabusCard />
            <SyllabusCard />
            <ProfileCard />
            <ProfileCard />
            <SyllabusCard />
            <BadgeCard />
        </div>
    </section>
    
    
</template>