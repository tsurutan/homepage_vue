<template>
  <div>
    <p class="profile__description-title">Experience</p>
    <p class="profile__description-item">OneBox Inc. 2018 -</p>
    <p class="profile__description-content">CTO, developing cryptocurrency services.</p>
    <p class="profile__description-item">Recruit Inc. 2017 - 2018</p>
    <p class="profile__description-content">Engineer, developing Jalan which is most popular trip adviser app in Japan.</p>
    <p class="profile__description-item">MICIN Inc. 2016 - 2017</p>
    <p class="profile__description-content">Engineer, developing android application and machine learning.</p>
    <p class="profile__description-item">Redish Inc. 2016 - </p>
    <p class="profile__description-content">Engineer, developing android application.</p>
    <p class="profile__description-item">Drivemode Inc. 2016 - 2017</p>
    <p class="profile__description-content">Engineer, developing android application.</p>
    <p class="profile__description-item">FreakOut Inc. 2015 - 2016</p>
    <p class="profile__description-content">Engineer, developing android application.</p>
    <p class="profile__description-item">Translimit Inc. 2015 - 2016</p>
    <p class="profile__description-content">Engineer, developing cocos2d-x application.</p>
    <p class="profile__description-item">Coincheck Inc. 2014 - 2016</p>
    <p class="profile__description-content">Engineer, developing android application and server.</p>
    <p class="profile__description-item">Fablic Inc. 2014 - 2016</p>
    <p class="profile__description-content">Engineer, developing android application and server.</p>
    <p class="profile__description-title">Education</p>
    <p class="profile__description-item">Tokyo institute of technology 2013 - 2017</p>
    <p class="profile__description-content">Major in computer science, natural languate processing.</p>
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

<style lang="sass">
.profile__description-title
  margin-top: 1rem
  font-size: .85rem
  font-family: inherit

.profile__description-item
  font-size: .75rem
  margin-top: 1rem

.profile__description-content
  color: #265125
  font-size: .75rem

.profile__description-item-date
  color: #265125
  font-size: .75rem

.profile__description
  background: #8AB20F
  border: 1.2px solid #414536
  padding: 2rem
  border-radius: 2px
  font-size: .85rem
  text-align: left
</style>
