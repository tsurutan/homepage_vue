<template>
  <div class="main-container">
    <pcHeader/>
    <div class="container">
      <div class="container__inner">
        <div class="profile__description-container">
          <frameHeader />
          <div class="profile__main-description-container">
            <div class="profile__light-container">
              <div class="profile__light"/>
              <p class="profile__battely">BATTELY</p>
            </div>
            <div class="profile__description-inner">
              <nuxt/>
            </div>
          </div>
        </div>
        <div class="profile__main-container">
          <h2 class="profile__subtitle">
            Engineer
          </h2>
          <h1 class="profile__title">
            Atsuhiro Tsuruta
          </h1>
        </div>
        <div class="game-pad__first-container">
          <gamePad/>
          <abButton/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navigation from '~/components/Navigation.vue'
import PcHeader from '~/components/PcHeader.vue'
import FrameHeader from '~/components/FrameHeader.vue'
import GamePad from '~/components/GamePad.vue'
import AbButton from '~/components/AbButton.vue'

export default {
  components: {
    Navigation,
    PcHeader,
    FrameHeader,
    GamePad,
    AbButton
  }
}
</script>

<style lang="sass">
@import "~/assets/css/media.sass"
html
  font-family: 'NintendBold'
  font-size: 16px
  word-spacing: 1px
  -ms-text-size-adjust: 100%
  -webkit-text-size-adjust: 100%
  -moz-osx-font-smoothing: grayscale
  -webkit-font-smoothing: antialiased
  box-sizing: border-box
  @include media_below_large
    font-size: 14px

*
  box-sizing: border-box
  margin: 0
  &:before, &:after
    box-sizing: border-box
    margin: 0

.game-pad__first-container
  display: flex
  margin-top: 2rem
  justify-content: space-between
.container__inner
  width: 100%

.main-container
  max-width: 500px
  margin: 0 auto

.container
  display: flex
  justify-content: center
  text-align: center
  padding: 1rem 2.5rem
  width: 100%
  height: calc(100vh - 3rem)
  border: 2px solid gray
  background: #B0B0B0

.profile__main-container
  display: flex
  align-items: center
  margin: 0 auto

.profile__image
  width: 7rem
  height: 7rem
  margin-right: 2rem
  border-radius: 50%
  margin-bottom: 1rem

.profile__title
  font-size: 1.6rem
  font-weight: normal
  text-align: center
  color: #221D6D
  @include media_below_large
    font-size: 1.2rem

.profile__subtitle
  font-weight: normal
  color: #221D6D
  border: 3px solid #221D6D
  padding: .2rem
  font-size: .9rem
  border-radius: 12px
  margin-right: .5rem

.profile__description-container
  background: #6D6D6D
  border: 1.2px solid #414536
  border-radius: 12px 12px 50px 12px
  margin: 0 auto .5rem

.profile__main-description-container
  display: flex
  align-items: center
  width: 100%

.profile__light-container
  margin-top: -4rem

.profile__light
  height: .8rem
  width: .8rem
  border-radius: 50%
  background: #FB0005
  margin: 0 auto .5rem

.profile__battely
  font-size: .65rem
  color: #909090
  padding: 0 .5rem

.profile__description-inner
  font-family: 'EarlyGameBoy'
  background: #8AB20F
  border: 1.2px solid #414536
  padding: .5rem
  width: 100%
  height: 14rem
  overflow-y: scroll
  border-radius: 2px
  margin: 1rem 4rem 2rem 0
  font-size: .85rem
  text-align: left
  @include media_below_large
    margin: 1rem 2rem 2rem 0
</style>
