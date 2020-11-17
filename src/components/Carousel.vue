<template>
    <div class="carousel">
        <slot></slot>

        <button @click="next" class="next">&#x3e;</button>
        <button @click="prev" class="prev">&#x3c;</button>
    </div>
</template>

<script>
export default {
    data() {
        return {

        }
    },

    methods: {
        next () {
            this.$emit('next');
        },

        prev () {
            this.$emit('prev');
        }
    }
}
</script>

<style>
    @import '../assets/styles/style.css';
</style>
