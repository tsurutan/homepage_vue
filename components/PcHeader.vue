<template>
  <div class="pc-header">
    <div class="pc-header__left"/>
    <div>
      <div class="pc-header__vertical-line-container">
        <div class="pc-header__vertical-line"/>
        <div class="pc-header__vertical-line"/>
        <div class="pc-header__vertical-line"/>
      </div>
      <p class="pc-header__on-off">ON・OFF</p>
    </div>
    <div class="pc-header__right"/>
  </div>
</template>

<style lang="sass">
$border-color: #6D6D6D
$pc-header-height: 2.5rem
.pc-header
  display: flex
  height: $pc-header-height
  border: 1px solid gray
  border-radius: 20px 20px 0 0
  border-bottom: 8px solid $border-color
  background: #B0B0B0

.pc-header__left
  height: $pc-header-height
  width: 3rem
  border-right: 6px solid $border-color
  margin-right: 1rem

.pc-header__right
  height: $pc-header-height
  width: 3rem
  border-left: 6px solid $border-color
  margin-left: auto

.pc-header__vertical-line-container
  display: flex
  padding-left: .5rem

.pc-header__vertical-line
  width: 8px
  background: $border-color
  height: .8rem
  margin-right: 2px

.pc-header__on-off
  border: 1px solid $border-color
  border-radius: 8px
  color: $border-color
  height: .85rem
  padding: 0 .5rem
  font-size: .75rem
</style>
