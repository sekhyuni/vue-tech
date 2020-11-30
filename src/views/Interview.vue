<template>
  <section class="interview">
    <header>
      <h1>This is an interview page</h1>
      <img alt="Naver logo" src="../assets/naver.png">
    </header>

    <article>
      <Naver msg="Welcome to Infomation of Naver"/>
    </article>
  </section>
</template>

<script>
// @ is an alias to /src
import Naver from '@/components/Naver.vue'

export default {
  name: 'Home',
  components: {
    Naver
  }
}
</script>

<style scoped lang="scss">
$base-color: #00FF00;

h1 {
  color: desaturate($base-color, 40%);
}
</style>