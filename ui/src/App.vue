<template>
  <div id="app" class="container-md">
    <heading/>
    <router-view/>
    <heading/>
  </div>
</template>

<script>
import Heading from '@/components/Heading'

export default {
  components: {
    Heading
  }
}
</script>
