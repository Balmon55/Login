<template>
  <div id="app">
    <div class="button">
    <div id="nav">
    <button> <router-link to="/about">Register</router-link> </button>
     <button><router-link to="/">Login</router-link>  </button>  
      
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  text-align: left;
  
}

#nav {
  margin-top:0px;
  
 
  
}

#nav a {
  font-weight: bold;
  color: white;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.button{
 float: right;
 background-color:rgba(19, 35, 47, 0.9);
 width: 100%;
 margin: 0px;
 
}
button{

background-color:rgba(18, 41, 59, 0.9);
border: none;
color: white;
padding: 15px 32px;
text-align: center;
text-decoration: none;
display: inline-block;
font-size: 16px;
float: right;
}





</style>
