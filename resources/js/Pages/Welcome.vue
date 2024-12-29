<script setup lang="ts">
import { Button } from '@/shadcn/ui/button';
import { Head } from '@inertiajs/vue3';
defineProps<{
    canLogin?: boolean;
    canRegister?: boolean;
    laravelVersion: string;
    phpVersion: string;
}>();

// function handleImageError() {
//     document.getElementById('screenshot-container')?.classList.add('!hidden');
//     document.getElementById('docs-card')?.classList.add('!row-span-1');
//     document.getElementById('docs-card-content')?.classList.add('!flex-row');
//     document.getElementById('background')?.classList.add('!hidden');
// }
</script>

<template>
    <Head title="Welcome" />
    <h1 class="bg-green-400 text-red-400">This is a sample</h1>
    <Button>This si button</Button>
</template>
