<template>
  第七周作業這是前台頁面
  <button type="button" class="btn btn-primary">Primary</button>
  <router-link to="/">Home</router-link> |
  <router-link to="/about">About</router-link> |
  <router-link to="/products">Products</router-link> |
  <router-link to="/cart">Cart</router-link> |
  <router-link to="/login">登入</router-link> |
  <router-link to="/admin/products">後臺產品列表</router-link> |
  <hr/>
  <router-view></router-view>
</template>

<script>
import { RouterView } from 'vue-router'

export default {
  components: {
    RouterView
  }
}
</script>
