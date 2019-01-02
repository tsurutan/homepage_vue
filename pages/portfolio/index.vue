<template>
  <div class="container">
    <div>
      <h1 class="title">
        tsurutan_homepage
      </h1>
      <h2 class="subtitle">
        My homepage created by nuxt js
      </h2>
    </div>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: `ATSUHIRO TSURUTA PORTFOLIO`,
      meta: [
        { hid: 'description', name: 'description', content: 'Atsuhiro Tsuruta(鶴田 篤広)のポートフォリオです' }
      ]
    }
  }
}
</script>
