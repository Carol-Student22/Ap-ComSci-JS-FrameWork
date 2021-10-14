<template>
  <div class="home">
    <Start msg="Hi"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Start from '@/components/Start.vue'

export default {
  name: 'Home',
  components: {
    Start
  }
}
</script>
