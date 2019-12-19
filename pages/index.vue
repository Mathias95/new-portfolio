<template>
  <div>
    <MenuHeader />
    <Banner />
    <section class="experience">
      <div class="experience__wrapper">
        <div class="experience__wrapper--inner">
          <h3>Creating interactive experiences</h3>
          <ul class="experience__list">
            <li class="experience__item">
              Frontend development
            </li>
            <li class="experience__item">
              Web design
            </li>
            <li class="experience__item">
              UX/UI Desktop
            </li>
          </ul>
        </div>
      </div>
      <div class="experience__img">
        <img src="" alt="my personal experiences" />
      </div>
    </section>
    <section class="skills">
      <div class="container">
        <div class="row">
          <div class="col">
            <h3>Little about me</h3>
            <p>
              Min tekniske værktøjskasse råder over forskellige programmer, samt
              værktøjer som bliver anvendt i forbindelse med udviklingsprocessen
              af hjemmesider. Jeg har blandt andet arbejdet med CMS systemet
              Wordpress, samt Umbraco. Det seneste værktøj, som jeg har kastet
              mig over at lærer er Frameworket Vue.js, samt app sproget Swift
              til ios development, da jeg finder app udvikling spændende.
            </p>
            <nuxt-link to="/">
              See my cv
            </nuxt-link>
          </div>
          <div class="col">
            <img src="" alt="Picture of skill set" />
          </div>
        </div>
      </div>
    </section>
    <section class="contact">
      <div class="container">
        <div class="row">
          <div class="col">
            <span>Let's work together</span>
            <h2>mathiasrjacobsen@gmail.com</h2>
            <p>
              Kunne du tænkte dig, at vide mere om mine kompetencer eller
              projekter. Så er du velkomment til at kontakte mig.
            </p>
            <SocialIcons />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import MenuHeader from '~/components/MenuHeader.vue'
import Banner from '~/components/Banner.vue'
import SocialIcons from '~/components/SocialIcons.vue'

export default {
  components: {
    MenuHeader,
    Banner,
    SocialIcons
  }
}
</script>
