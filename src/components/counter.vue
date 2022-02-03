<template>
<h1 class="title">Welcome to Counter Application</h1>
<div class="counter-box">
<div class="box">
    <h1>Counter: {{count}} </h1>
</div>
<div id ="counter-app">
<button class="button-1" @click="increment">Increment</button>
<button class="button-2" @click="reset">Reset</button>
<button class="button-3" @click="decrement">Decrement</button>
</div>
</div>
</template>
<script>

export default 
    {
        name:'Counter',
    }
</script>
<style>

</style>
