<template>
<div class="container">
    <h1>Counter: {{counter}}</h1>
    <div>
    <button @click='onIncrement' class="btn btn-success">Plus</button>
    <button @click='onDecrement' class="btn btn-danger">Munis</button>
    </div>
</div>
</template>

<script>
    export default {
        data(){
            return{
                counter: 0,
            };
        },
    methods: {
        onIncrement() {
            this.counter += 1
        },
        onDecrement() {
            this.counter -= 1
        },
    },
    };

</script>

<style>
</style>
