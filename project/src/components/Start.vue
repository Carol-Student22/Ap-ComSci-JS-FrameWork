<template>
    <section id="main" class="to-be-changed-later">
        <h1 class="title">Random Title - Temporary Placement </h1>
        <h1>{{ msg }}</h1>

    </section>
</template>

<script>
export default {
  name: 'Start',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
#main {
    background-color: red ;
}

</style>