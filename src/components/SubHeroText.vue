<template>
    <div>
        <h1 class="mt-3">{{ text }}</h1>
    </div>
</template>

<script>

export default {
    name: 'SubHeroText',
    props: {
        text: { type: String, default: '' },
    }
}
</script>

<style scoped>

</style>