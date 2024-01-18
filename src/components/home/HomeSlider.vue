<script setup>
import HomeActions from '@/components/home/HomeAcctions.vue'
</script>

<template>
    <section class="slider">
        <img src="@/assets/img/house.jpg" alt="Imagen de casa nombre de tu empresa" class="slider-hero">
        <div class="slider-content">
           <h2 class="slider-title">
                Aprendiendo vuejs3 en el 2024
           </h2>
           <p class="slider-description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit assumenda maiores tenetur ullam aspernatur placeat mollitia.
           </p>
        </div>
        
        <div class="slider-card">
            <HomeActions/>
           </div>
    </section>
</template>