<template>
  <div class="link">
    <instagram-logo class="logo"/>
    flash_holiday
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
.link {
  display: flex;
  align-items: center;
}
</style>
