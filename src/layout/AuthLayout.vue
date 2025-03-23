<template>
  <div class="d-flex vh-100 justify-content-center align-items-center">
    <div class="card p-4 shadow-lg" style="width: 350px">
      <h3 class="text-center mb-4">Вход</h3>
      <form @submit.prevent="login">
        <div class="mb-3">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email" required />
        </div>
        <div class="mb-3">
          <label for="password" class="form-label">Пароль</label>
          <input type="password" class="form-control" id="password" required />
        </div>
        <button type="submit" class="btn btn-primary w-100">Войти</button>
      </form>
    </div>
  </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>