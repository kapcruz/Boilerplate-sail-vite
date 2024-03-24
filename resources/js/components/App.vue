<template>
    <div class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center py-4 sm:pt-0 text-sky-500 hover:text-sky-600">
    <h1>{{ greeting }}</h1>
    </div>
</template>
<script>
export default {
    setup: () => ({
        greeting: 'Hello World from Vue!'
    })
}
</script>
