<template>
<h1 class="title">Welcome to Counter Application</h1>
<div class="counter-box">
<div class="box">
    <h1>Counter : {{count}} </h1>
</div>
</div>
<div id ="counter-app"> 
<button class="button-1" @click="increment">Increment</button>
<button class="button-2" @click="reset">Reset</button>
<button class="button-3" @click="decrement">Decrement</button>
</div>

</template>
<script>

export default 
    {
        name:'Counter',
    }
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Poppins:wght@300;400&family=Ubuntu:wght@300&display=swap');
h1{
display: flex;
justify-content: center;
align-items: center;
height: 20vh;
font-family: 'Poppins', sans-serif;
width: 99%;
}
#counter-app{
 display: flex;
justify-content: center;
align-items: center;
gap :2rem;
}
.counter-box ,.box
{
display:flex;
justify-content: center;
align-items: center;
 padding-bottom: 2rem;
}
.box{
    width: 355px;
    height:15vh;
    border: 1px solid green;
    border-radius:8px;
    
}
.button-1,.button-2,.button-3 {
  border-radius: 8px;
  border-style: none;
  box-sizing: border-box;
  color: #FFFFFF;
  cursor: pointer;
  font-family: 'Poppins', sans-serif;
  font-size: 14px;
  height: 40px;
  width:100px;
  line-height: 20px;
  transition: 0.5s ease;
  margin: 0;
  outline: none;
  padding: 10px 16px;
  position: relative;
  text-align: center;
}
.button-1{
    background-color:#2ea44f;
}
.button-1:hover {
  background-color:#175c2b ;
}
.button-2 {
  background-color: #b3abab;
}
.button-2:hover {
  background-color: #5e5858;
}
.button-3 {
  background-color: #EA4C89; 
}
.button-3:hover {
background-color: #bd0a4e;
}
</style>
