<template>
  <section class="banner">
    <div class="container">
      <div class="row banner__wrapper">
        <div class="col">
          <h1 class="banner__title">
            Hi, my name is <span class="banner__title--red">Mathias</span> I am
            a webdeveloper &amp; designer
          </h1>
          <p class="banner__subtitle">
            I am always up for new challenges...
          </p>
        </div>
      </div>
    </div>
    <ScrollDown />
  </section>
</template>

<script>
import ScrollDown from '~/components/ScrollDown.vue'

export default {
  components: {
    ScrollDown
  }
}
</script>
