<template>
  <div class="p-3">
    <h4 class="text-info text-center">Почему стоит рабоать с нами</h4>
    <div class="m-3">
      <div>
        <christmas-tree class="icon"/>
        причина
      </div>
    </div>
    <div class="text-center">
      <button type="button" class="btn btn-primary">
        Пригласить
      </button>
    </div>
  </div>
</template>

<script>
import ChristmasTree from '@/assets/svg/christmas-tree.svg'
export default {
  components: {
    ChristmasTree
  }
}
</script>
