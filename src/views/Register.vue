<template>
  <div class="register">
    <form action class="form1" @submit.prevent="register">
      <label class="form-label1" for="#email">Email:</label>
      <input
        v-model="email"
        class="form-input1"
        type="email"
        id="email"
        required
        placeholder="Email"
      >
      <label class="form-label1" for="#password">Password:</label>
      <input
        v-model="password"
        class="form-input1"
        type="password"
        id="password"
        placeholder="Password"
      >
      <label class="form-label1" for="#password-repeat">Repite la contraeña:</label>
      <input
        v-model="passwordRepeat"
        class="form-input1"
        type="password"
        id="password-repeat"
        placeholder="Password"
      >
      <input class="form-submit1" type="submit" value="Sign Up">
    </form>
  </div>
</template>
<script>
export default {
  
}
</script>
<style>
.register {
  padding: 69px;
}
.form1 {
  margin: 90px auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 20%;
  min-width: 350px;
  max-width: 100%;
  background: rgba(19, 35, 47, 0.9);
  border-radius: 5px;
  padding: 40px;
  box-shadow: 0 4px 10px 4px rgba(0, 0, 0, 0.3);
}
.form-label1 {
  margin-top: 2rem;
  color: white;
  margin-bottom: 0.5rem;

    margin-top: 0rem;
  
}
.form-input1 {
  padding: 10px 15px;
  background: none;
  background-image: none;
  border: 1px solid white;
  color: white;

    outline: 0;
    border-color: #1ab188;
}
.form-submit1 {
  background: #1ab188;
  border: none;
  color: white;
  margin-top: 1rem;
  padding: 1rem 0;
  cursor: pointer;
  transition: background 0.2s;
  background: #0b9185;
  
}
.error {
  margin: 1rem 0 0;
  color: #ff4a96;
}


</style>

