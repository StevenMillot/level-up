<template>
  <div class="hello">
    <form class="form-login" action="" method="post required" autocomplete="on">
      <div class="form-inputs">
        <label for="uname"><b>Username/Login</b></label>
        <input type="text" id="uname" placeholder="Enter Username" name="username" required>

        <label for="userPsw"><b>Password</b></label>
        <input type="password" id="userPsw" placeholder="Enter Password" name="user-password" required>
      </div>

        <label>
          <input type="checkbox" checked="checked" name="remember"> Remember me
        </label>

        <button type="submit">Connect</button>
    </form>

    <h1>{{ msg }}</h1>



  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
.form-login {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  .form-inputs {
    display: flex;
    flex-direction: column;
    max-width: 30rem;

    label {
      font-size: 1.2rem;
    }

    input {
      margin: 0.4rem 0 1rem;
    }
  }

  button {
    margin: 1rem;
  }
}


h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
