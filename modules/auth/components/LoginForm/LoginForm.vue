<script setup lang="ts">
interface LoginForm {
  email: string;
  password: string;
}

const form = ref<LoginForm>({
  email: "",
  password: "",
});
</script>

<template>
  <div class="flex flex-col items-center">
    <div class="mb-5">
      <el-input
        v-model="form.email"
        type="email"
        placeholder="Email"
        style="margin-bottom: 16px"
      />
      <el-input
        v-model="form.password"
        type="password"
        placeholder="Password"
      />
    </div>

    <el-button type="primary">Entrar</el-button>
  </div>
</template>
