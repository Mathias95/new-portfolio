<template>
  <div>
    <MenuHeader />
    <Banner />
    <section class="projects">
      <h2 class="projects__title-bg">
        Web Developer
      </h2>
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-8 col-lg-6">
            <h2 class="projects__title title-2">
              My selected<br />
              projects
            </h2>
            <p class="projects__text main-text">
              Nedenfor kan du se et udpluk over de varieret projekter, som jeg
              har udarbejdet gennem tiden. Projekterne indeholder både Web
              Design, samt udvikling
            </p>
            <nuxt-link to="/" class="projects__link">
              See all projects
            </nuxt-link>
          </div>
          <div class="col-custom">
            <FrontProjectSlider class="projects__slider" />
          </div>
        </div>
      </div>
    </section>
    <section class="experience">
      <div class="container-full">
        <div class="row-full">
          <div class="col-full experience__wrapper">
            <div class="experience__wrapper--inner">
              <h2 class="experience__title title-2">
                Creating interactive experiences
              </h2>
              <ul class="experience__list">
                <li class="experience__list-item">
                  Frontend development
                </li>
                <li class="experience__list-item">
                  Web design
                </li>
                <li class="experience__list-item">
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
    <section class="skills section-top">
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-8 col-lg-6">
            <h2 class="skills__title title-2">
              Little about me
            </h2>
            <p class="skills__text main-text">
              Min tekniske værktøjskasse råder over forskellige programmer, samt
              værktøjer som bliver anvendt i forbindelse med udviklingsprocessen
              af hjemmesider. Jeg har blandt andet arbejdet med CMS systemet
              Wordpress, samt Umbraco. Det seneste værktøj, som jeg har kastet
              mig over at lærer er Frameworket Vue.js, samt app sproget Swift
              til ios development, da jeg finder app udvikling spændende.
            </p>
            <nuxt-link to="/" class="skills__cv">
              See my cv
            </nuxt-link>
          </div>
          <div class="col-12 col-lg-6 skills__img-wrapper">
            <img src="" alt="Picture of skill set" />
          </div>
        </div>
      </div>
    </section>
    <section class="contact section-top section-bottom">
      <div class="container">
        <div class="row">
          <div class="col text-center">
            <div class="contact__text-wrapper">
              <span class="contact__title">Let's work together</span>
              <h3 class="contact__mail">
                mathiasrjacobsen@gmails
                <span class="contact__mail--circle">&nbsp;</span>com
              </h3>
              <p class="contact__text main-text">
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
