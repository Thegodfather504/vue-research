<script setup lang="ts">
import VehicleEntry from '@/components/VehicleEntry.vue';
</script>


<template>
    <div class="submission">
        <h1> OnCall Ticket Submission </h1>
        <VehicleEntry />

    </div>
   
</template>

<style>

@media (min-width: 1024px){
    .submission {
        min-height: 100vh;
        display: flex;
        align-items: center;
    }
}
</style>