<template>
    <div>
        <h1>{{title}}</h1>
        <p>Counter: {{counter}}</p>
        <button @click="increment">Click me!</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'Hello Vue',
            counter: 0
        }
    }, 
    methods: {
        increment( evt ) {
            this.counter++;
        }
    }
}
</script>