<script setup lang="ts">
import LoginForm from '@/modules/auth/components/LoginForm/LoginForm.vue';

</script>
<template>
  <div
    class="container mx-auto flex flex-col items-center justify-center h-screen py-9"
  >
    <div
      class="flex flex-col gap-5 justify-evenly items-center shadow-md w-full max-w-80 min-h-96 px-3 py-5"
    >
      <h1 class="text-3xl">Login</h1>
    <LoginForm />
    </div>
  </div>
</template>
