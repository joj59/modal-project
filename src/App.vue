<template>
    <h1>{{ title }}</h1>
    <Modal header="hello">
        <p>modal slot</p>
        <h1>sloots</h1>
    </Modal>
</template>

<script>
import Modal from './components/Modal.vue';

export default {
    name: 'App',
    components: {
        Modal,
    },
    data() {
        return {
            title: 'My First Vue Project',
        };
    },
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
