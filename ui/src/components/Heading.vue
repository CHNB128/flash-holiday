<template>
  <div class="navbar navbar-dark bg-primary">
    <a class="navbar-brand">
      <instagram-logo class="logo"/>
      flash_holiday
    </a>
    <span class="navbar-text">
      Tel: +7 777 777 77 77
    </span>
  </div>
</template>

<script>
import InstagramLogo from '@/assets/svg/instagram.svg'

export default {
  components: {
    InstagramLogo
  }
}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/colors.scss';

.navbar {
}
</style>
