<template>
  <div class="frame-header">
    <div class="frame-header__left">
      <div class="frame-header__purple-bar"/>
      <div class="frame-header__blue-bar"/>
    </div>
  </div>
</template>

<style lang="sass">
.frame-header
  padding: .3rem 2rem 0
  display: flex
  align-items: center

.frame-header__left
  width: 30%

.frame-header__purple-bar
  height: 6px
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
