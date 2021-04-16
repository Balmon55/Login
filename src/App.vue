<template>
  <div id="app">
    <div class="button">
    <div id="nav">
      <button><router-link to="/login">Login</router-link>  </button>  
    <button> <router-link to="/register">Register</router-link> </button>
      </div>
    </div>
    <router-view/>
  </div>
 
</template>

<style>
#app {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  text-align: left;
   background-color:rgba(18, 49, 73, 0.9);
  
}

#nav {
  margin-top:8px;
  
 
  
}

#nav a {
  font-weight: bold;
  color: white;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.button{
 background-color:rgba(18, 49, 73, 0.9);
 width: 100%;
 margin: 0px;
 
 
}
button{
background-color:rgba(18, 49, 73, 0.9);
border: none;
color: white;
padding: 15px 32px;
text-align: center;
text-decoration: none;
display: inline-block;
font-size: 20px;
}
</style>
