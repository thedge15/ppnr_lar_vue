<script setup>
</script>
<template>
    <div>
        <div class="mx-auto pt-5 pb-5 font-serif">
            <nav class="flex justify-center h-8">
                <a :href="route('main')" class="w-32 hover:text-xl">Главная</a>
                <a :href="route('about')" class="w-32 hover:text-xl">О нас</a>
                <a :href="route('services')" class="w-32 hover:text-xl">Услуги</a>
                <a :href="route('contacts')" class="w-32 hover:text-xl">Контакты</a>
            </nav>
            <div class="text-center mt-5">
            <h2 class="text-2xl">Разработка программ ПНР, программ и методик приёмочных испытаний слаботочных
                сетей.</h2>
            </div>
            <slot class="h-5/6" />
        </div>
    </div>
</template>
<style scoped>

</style>
