<template>
  <div id="app">
    <router-view></router-view>
    <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
  import MainTabBar from "components/content/mainTabBar/MainTabBar";
import Home from 'views/Home'
import Category from 'views/Category'
import Cart from 'views/Cart'
import Profile from 'views/Profile'

export default {
  name: 'App',
  components: {
    MainTabBar,
    Home,
    Category,
    Cart,
    Profile
  }
}
</script>

<style>
  @import "./assets/css/base.css";
</style>
