<template>
  <div class="main-container">
    <pcHeader/>
    <div class="container">
      <div>
        <div class="profile__description-container">
          <frameHeader />
          <div class="profile__description-inner">
            <nuxt/>
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
      </div>
    </div>
  </div>
</template>

<script>
import Navigation from '~/components/Navigation.vue'
import PcHeader from '~/components/PcHeader.vue'
import FrameHeader from '~/components/FrameHeader.vue'

export default {
  components: {
    Navigation,
    PcHeader,
    FrameHeader
  }
}
</script>

<style lang="sass">
html
  font-family: 'NintendBold'
  font-size: 16px
  word-spacing: 1px
  -ms-text-size-adjust: 100%
  -webkit-text-size-adjust: 100%
  -moz-osx-font-smoothing: grayscale
  -webkit-font-smoothing: antialiased
  box-sizing: border-box

*
  box-sizing: border-box
  margin: 0
  &:before, &:after
    box-sizing: border-box
    margin: 0

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
  font-size: 1.8rem
  font-weight: normal
  text-align: center
  color: #221D6D

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
  border-radius: 8px 8px 50px 8px
  margin: 0 auto .5rem

.profile__description-inner
  font-family: 'EarlyGameBoy'
  background: #8AB20F
  border: 1.2px solid #414536
  padding: .5rem
  height: 30vh
  overflow-y: scroll
  border-radius: 2px
  margin: 1rem 4rem 2rem
  font-size: .85rem
  text-align: left
</style>
