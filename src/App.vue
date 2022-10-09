<script>
import Header from './components/Header/Header.vue';


export default{
  
  name: 'Owhab',
  components: Header,
  data(){
    return{
      count: 0,
    }

  },

}

</script>

<template>

      <Header/>
   
      <h1>Hello World</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sit tenetur cum voluptates optio sequi quod odit, adipisci non, dolor sint neque assumenda nam quis voluptatibus qui aliquam est, minus quas!</p>
      <h2>Counter {{count}} </h2>
      <button @click="count++">Increment</button>
      <button @click="count--">Decrement</button>
    

</template>

<style scoped>
</style>
