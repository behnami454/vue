<template>
  <div id="users">
  
    <navbar />
    <card />
    
    <div>
      <ul  v-for="todo in todos" :key="todo.id">
        <li>{{todo.name}} , {{todo.username}}</li>

      </ul>
    </div>
    <div id="fooot"><footerr /></div>
    
   

  </div>
    

 
    
</template>
<script>
import navbar from './navbar'
import card from './card'
import axios from 'axios'
import footerr from './footerr'



export default {
  name : 'users',
  components:{
    navbar,
    card,
    footerr
    
    
  },
  data: () => ({
    todos: []
    
  }),
  mounted: function() {
   
    axios.get('https://jsonplaceholder.typicode.com/users').then((result) => {
      this.todos = result.data;
    })
   
  },
}
  
    
  





</script>
<style>
#fooot{
  background-color: black;
    margin-top: 10px;
}
ul{
  text-align: center;
}
li{
  list-style: none;
  text-align: center;
  
    font-size: 25px;
    margin: auto;
    font-family: none;
}

 
</style>
