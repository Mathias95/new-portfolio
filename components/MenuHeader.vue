<template>
  <header class="header">
    <div class="header__wrapper container-custom container-custom--fluid">
      <nuxt-link class="header__logo-link" to="/">
        <Logo />
      </nuxt-link>
      <button class="header__menu-button trans-fast">
        <span class="header__menu-text">Menu</span>
        <div class="header__menu-wrapper">
          <span class="burgerbar burgerbar--1">&nbsp;</span>
          <span class="burgerbar burgerbar--2">&nbsp;</span>
          <span class="burgerbar burgerbar--3">&nbsp;</span>
        </div>
      </button>
    </div>
  </header>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>
