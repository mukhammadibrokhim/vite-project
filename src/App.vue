<template>
    <div class="container">
        <h1>Counter: {{ counter }}</h1>
        <div class="d-flex">
         <button @click="onIncreament" type="button" class="btn btn-outline-success">Addition</button>
         <button @click="onDecrement" type="button" class="btn btn-outline-danger">Decrement</button>
        </div>
    </div>
</template>

<script>
 export default {
    data() {
        return {
            counter: 0
        }
    },
    methods: {
        onIncreament(){
            this.counter +=1
        },
        onDecrement(){
            this.counter -=1
        }
    },  
 }
</script>

<style>

</style>