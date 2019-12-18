<template>
  <div>
    <MenuHeader />
    <Banner />
  </div>
</template>

<script>
import MenuHeader from '~/components/MenuHeader.vue'
import Banner from '~/components/Banner.vue'

export default {
  components: {
    Banner,
    MenuHeader
  }
}
</script>
