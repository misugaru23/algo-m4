<script setup>
import CardSeasones from "../components/CardSeasones.vue"
</script>


<template>
    <section>
        <CardSeasones v-for="i in 5" :key="i"/>
    </section>
</template>