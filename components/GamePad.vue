<template>
  <div class="game-pad">
    <div class="game-pad__up"/>
    <div class="game-pad__center-container">
      <div class="game-pad__left"/>
      <div class="game-pad__center"/>
      <div class="game-pad__right"/>
    </div>
    <div class="game-pad__down"/>
  </div>
</template>

<style lang="sass">
.game-pad
  width: 8rem
  height: 8rem
  border: 1px solid gray
  padding: 1rem
  border-radius: 50%

.game-pad__up
  width: 2rem
  height: 2rem
  background: #313131
  cursor: pointer
  border-top: 1px solid black
  border-left: 1px solid black
  border-right: 1px solid black
  margin: 0 auto

.game-pad__down
  width: 2rem
  height: 2rem
  background: #313131
  cursor: pointer
  border-bottom: 1px solid black
  border-left: 1px solid black
  border-right: 1px solid black
  margin: 0 auto

.game-pad__center
  width: 2rem
  height: 2rem
  background: #313131

.game-pad__left
  width: 2rem
  height: 2rem
  background: #313131
  cursor: pointer
  border-top: 1px solid black
  border-left: 1px solid black
  border-bottom: 1px solid black

.game-pad__right
  width: 2rem
  height: 2rem
  cursor: pointer
  background: #313131
  border-top: 1px solid black
  border-right: 1px solid black
  border-bottom: 1px solid black

.game-pad__center-container
  display: flex
  justify-content: center
</style>
