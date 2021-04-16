<template>
  <div class="Login">
    <form action class="form">
      <label class="form-label" for="#email">Email:</label>
      <input class="form-input" type="email" id="email" required placeholder="Email">
      <label class="form-label" for="#password">Password:</label>
      <input class="form-input" type="password" id="password" required placeholder="Password">
      <input class="form-submit" type="submit" value="Login">
      
    </form>
   
  </div>
</template>

<script>

export default {
  name: 'Login',
  components: {
    
  }
}
</script>
<style >
.Login {
  padding: 2rem;
}

.form {
  margin: 9rem auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 100%;
  min-width: 35px;
  max-width: 450px;
  background:rgba(19, 35, 47, 0.9)  ;
  border-radius: 5px;
  padding: 40px;
  box-shadow: 0 4px 10px 4px rgba(0, 0, 0, 0.3);
}
.form-label {
  margin-top: 2rem;
  color: white;
  margin-bottom: 0.5rem;
  margin-top: 0rem;
  
}
.form-input {
  padding: 10px 15px;
  background: none;
  background-image: none;
  border: 1px solid white;
  color: white;
  outline: 0;
  border-color: #1ab188;
  margin-bottom: 18px;
  
  
}

.form-submit {
  background: #1ab188;
  border: 5px;
  color: white;
  margin-top: 1rem;
  padding:  8px 0;
  background: #0b9185;
  text-anchor:initial;
  font-size: 20px;
  width: 100%;
  float: right;
  
  }
 
</style>
