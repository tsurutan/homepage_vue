<template>
  <div class="pc-header">
    <div class="pc-header__left"/>
    <p class="pc-header__on-off">ON・OFF</p>
  </div>
</template>

<style lang="sass">
$border-color: #6D6D6D
.pc-header
  display: flex
  height: 3rem
  border-bottom: 8px solid $border-color

.pc-header__left
  height: 3rem
  width: 4rem
  border-right: 6px solid $border-color

.pc-header__on-off
  border: 1px solid $border-color
  border-radius: 8px
  color: $border-color
  height: 1.2rem
</style>
