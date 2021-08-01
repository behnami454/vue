<template>
  <div>
    <nav class="bg-dark mb-2 p-3"> 
  
      <router-link to="/" class="text-light m-auto p-5">Home </router-link>
      <router-link to="/users" class="text-light ">Users</router-link>
    </nav>
    <router-view />
  </div>
</template>