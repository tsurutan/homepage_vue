<template>
  <div>
    <div class="ab-button">
      <div class="ab-button__button"/>
      <p @click="tes" class="ab-button__button"/>
    </div>
    <div class="ab-button__text-container">
      <p class="ab-button__text">B</p>
      <p class="ab-button__text">A</p>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    tes (e) {
      alert('counter/add')
    }
  }
}

</script>

<style lang="sass">
.ab-button
  width: 10rem
  margin-top: 2rem
  height: 4.5rem
  display: flex
  padding: .5rem .8rem
  align-items: center
  justify-content: space-between
  border: 1px solid gray
  border-radius: 50px
  transform: rotate(-20deg)
  -moz-transform: rotate(-20deg)
  -webkit-transform: rotate(-20deg)

.ab-button__text
  color: #261F87
  text-align: center
  margin-left: 2.2rem
  &:nth-child(2)
    margin-left: 4rem

.ab-button__text-container
  display: flex
  padding: 0 .8rem
  margin-top: .3rem
  justify-content: space-around
  transform: rotate(-20deg)
  -moz-transform: rotate(-20deg)
  -webkit-transform: rotate(-20deg)

.ab-button__button
  cursor: pointer
  width: 3.5rem
  height: 3.5rem
  border-radius: 50%
  background: #6D1E50
</style>
