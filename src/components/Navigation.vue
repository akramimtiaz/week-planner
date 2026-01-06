<script setup lang="ts">
import { CheckCheck, House, SquareCheckBig, Calendar } from 'lucide-vue-next';
</script>

<template>
    <header class="w-[100%] flex flex-row justify-between items-center py-3 px-6 bg-white shadow-lg">
        <div class="flex flex-row gap-2 items-center">
            <CheckCheck color="#a2d1f6" :size="32" />
            <span class="text-2xl font-bold nav-title">Task Planner</span>
        </div>

        <nav class="flex flex-row">
            <ul class="flex flex-row gap-8">
                <li>
                    <a href="/" class="flex flex-row gap-2 items-center">
                        <House :size="16" />
                        <span>Home</span>
                    </a>
                </li>
                <li>
                    <a href="/tasks" class="flex flex-row gap-2 items-center">
                        <SquareCheckBig :size="16" />
                        <span>Tasks</span>
                    </a>
                </li>
                <li>
                    <a href="/planner" class="flex flex-row gap-2 items-center">
                        <Calendar :size="16" />
                        <span>Planner</span>
                    </a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
.nav-title {
    color: #121929;
}
</style>
