<template>
  <form class="p-3 bg-info">
    <slot/>
    <div class="form-group">
      <input class="form-control" type="text">
    </div>
    <div class="form-group">
      <input class="form-control" type="email" placeholder="Ваш Email">
    </div>
    <div class="form-group">
      <input class="form-control" type="text">
    </div>
    <div class="text-center">
      <button type="button" class="btn btn-primary">
        Оставить заказ
      </button>
    </div>
  </form>
</template>

<style lang="scss" scoped>
@import '@/assets/scss/colors.scss';

</style>
