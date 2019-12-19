<template>
  <section class="banner">
    <div class="banner__container container">
      <div class="row">
        <div class="banner__col">
          <div class="banner__text-wrapper">
            <h1 class="banner__title">
              Hi, my name is
              <strong class="banner__title--red">Mathias</strong><br />
              I am a webdeveloper &amp; designer
            </h1>
            <p class="banner__subtitle">
              Images on this site i for test purposes only...
            </p>
          </div>
          <ScrollDown />
        </div>
      </div>
    </div>
    <div class="banner__profile-img">
      &nbsp;
    </div>
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
