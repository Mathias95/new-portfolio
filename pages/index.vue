<template>
  <div>
    <MenuHeader />
    <Banner />
    <section class="projects">
      <h1>Web Developer</h1>
      <div class="container">
        <div class="row">
          <div class="col">
            <h2>My selected projects</h2>
            <p>
              Nedenfor kan du se et udpluk over de varieret projekter, som jeg
              har udarbejdet gennem tiden. Projekterne indeholder både Web
              Design, samt udvikling
            </p>
            <nuxt-link to="/">
              See all projects
            </nuxt-link>
          </div>
          <div class="col-custom">
            <FrontProjectSlider />
          </div>
        </div>
      </div>
    </section>
    <section class="experience">
      <div class="container-full">
        <div class="row-full">
          <div class="col-full experience__wrapper">
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
          <div class="col-full experience__img">
            <img src="" alt="my personal experiences" />
          </div>
        </div>
      </div>
    </section>
    <section class="skills">
      <div class="container">
        <div class="row">
          <div class="col-12 col-lg-6">
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
          <div class="col-12 col-lg-6">
            <img src="" alt="Picture of skill set" />
          </div>
        </div>
      </div>
    </section>
    <section class="contact">
      <div class="container">
        <div class="row">
          <div class="col text-center">
            <div class="contact__text-wrapper">
              <span class="contact__title">Let's work together</span>
              <h2 class="contact__mail">
                mathiasrjacobsen@gmails
                <span class="contact__mail--circle">&nbsp;</span>com
              </h2>
              <p class="contact__text">
                Kunne du tænkte dig, at vide mere om mine kompetencer eller
                projekter. Så er du velkomment til at kontakte mig.
              </p>
            </div>
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
import FrontProjectSlider from '~/components/FrontProjectSlider.vue'
import SocialIcons from '~/components/SocialIcons.vue'

export default {
  components: {
    MenuHeader,
    Banner,
    FrontProjectSlider,
    SocialIcons
  }
}
</script>
