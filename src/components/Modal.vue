<template>
    <div class="backdrop">
        <div class="modal">
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
