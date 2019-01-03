<template>
  <div class="frame-header">
    <div class="frame-header__left">
      <div class="frame-header__purple-bar"/>
      <div class="frame-header__blue-bar"/>
    </div>
    <p class="frame-header__title">TSURUTAN HOME PAGE</p>
    <div class="frame-header__right">
      <div class="frame-header__purple-bar"/>
      <div class="frame-header__blue-bar"/>
    </div>
  </div>
</template>

<style lang="sass">
.frame-header
  padding: .3rem 1rem 0
  display: flex
  align-items: center

.frame-header__left
  width: 100%
  margin-right: .5rem

.frame-header__right
  width: 100%
  margin-left: .5rem

.frame-header__title
  font-size: .75rem
  color: #878787
  white-space: nowrap

.frame-header__purple-bar
  height: .3rem
  border-radius: 8px
  background: #6D1E50
  width: 100%

.frame-header__blue-bar
  height: 4px
  margin-top: 4px
  border-radius: 8px
  background: #261F87
  width: 100%
</style>
