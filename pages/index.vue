<template>
  <div class="container">
    <div>
      <div class="profile__main-container">
        <img
          class="profile__image"
          src="~/assets/image/designer-pic.png" >
        <div>
          <h1 class="profile__title">
            Atsuhiro Tsuruta
          </h1>
          <h2 class="profile__subtitle">
            Engineer / UI UX Designer / Data Scientist
          </h2>
        </div>
      </div>
      <div class="profile__description-container">
        <div class="profile__description-inner">
          <p class="profile__description-title">
            Experience
          </p>
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
          <p class="profile__description-title">
            Education
          </p>
          <p class="profile__description-item">Tokyo institute of technology 2013 - </p>
          <p class="profile__description-content">Major in computer science, natural languate processing.</p>
        </div>
      </div>
    </div>
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
.container
  display: flex
  justify-content: center
  text-align: center
  margin-left: 15rem
  padding: 4rem 0
  width: 100%

.profile__main-container
  display: flex
  align-items: center
  width: 80%
  margin: 0 auto

.profile__image
  width: 7rem
  height: 7rem
  margin-right: 2rem
  border-radius: 50%
  margin-bottom: 1rem

.profile__title
  font-size: 1.8rem
  font-weight: normal
  text-align: center
  margin-bottom: .5rem
  color: #221D6D

.profile__subtitle
  font-size: 1rem
  font-weight: normal
  color: #221D6D

.profile__description-container
  background: #6D6D6D
  border: 1.2px solid #414536
  padding: 2rem 4rem
  border-radius: 8px 8px 50px 8px
  width: 80%
  margin: 2rem auto

.profile__description-inner
  background: #8AB20F
  border: 1.2px solid #414536
  padding: 2rem
  border-radius: 2px
  font-size: .85rem
  text-align: left

.profile__description-title
  margin-top: 1rem
  font-size: 1rem

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
