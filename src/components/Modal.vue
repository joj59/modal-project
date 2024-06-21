<template>
    <div class="backdrop">
        <div class="modal">
            <p>{{ header }}</p>
            <p>{{ header }}</p>

            <slot></slot>
        </div>
    </div>
</template>

<script>
export default {
    props: ['header'],
};
</script>

<style scoped></style>
