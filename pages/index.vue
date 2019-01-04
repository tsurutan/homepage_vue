<template>
  <div>
    <p class="profile__description-title">Menu</p>
    <router-link
      class="profile__description-content"
      to="/profile">Profile</router-link>
    <router-link
      class="profile__description-content"
      to="/portfolio">Portfolio</router-link>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: `ATSUHIRO TSURUTA`,
      meta: [
        { hid: 'description', name: 'description', content: 'Atsuhiro Tsuruta(鶴田 篤広)のホームページです' }
      ]
    }
  }
}
</script>
