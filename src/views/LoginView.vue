<script setup></script>

<template>
  <main>
    <div class="login">
      <div class="login__header">
        <h4>💰 Xpense Tracker</h4>
      </div>
      <div id="login">
        <div class="login_svg">
          <img src="@/assets/images/svg/login2.svg" alt="" />
        </div>
        <form class="form">
          <div class="form-input">
            <label>Enter Email</label>
            <input type="email" name="email" id="email" />
          </div>
          <div class="form-input">
            <label>Enter Password</label>
            <input type="password" name="password" id="password" />
          </div>
          <button type="submit">Login</button>
          <p class="signup">Don't have an account, <a href="register.html">Sign Up</a></p>
        </form>
      </div>
    </div>
  </main>
</template>
