<script setup>
import { reactive } from "vue";

const data = reactive({
  name: "",
  email: "",
  password: "",
  confirmPassword: "",
  errors: {},
  loading: false,
});
</script>

<template>
  <div>
    <div class="container">
      <div class="row">
        <div class="col-md-6 m-auto">
          <h1>Hallo dunia</h1>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
