<script setup lang="ts">
  import { Camera } from 'lucide-vue-next';
</script>

<template>
    <header class="border border-red-500 w-[100%] flex flex-row justify-between items-center py-3 px-6 bg-white shadow-lg">
        <div class="flex flex-row gap-2 items-center">
            <Camera color="red" :size="32" />
            Task Planner
        </div>

        <nav class="border border-blue-500 flex flex-row">
            <ul class="flex flex-row gap-4">
                <li>
                    Home
                </li>
                <li>
                    Tasks
                </li>
                <li>
                    Planner
                </li>
            </ul>
        </nav>
    </header>
</template>

<style scoped></style>
