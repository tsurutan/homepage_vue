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
        <p class="profile__description">
          I entered Tokyo institute of technology in 2013 and worked at Fablic, Coincheck, Translimit, FreakOut, Drivemode, MICIN, Redish、develping android application、server、data analyis.
          <br>
          <br>
          I do research on natural language processing dealing with review sentences when I was a college student.
          <br>
          <br>
          I was awarded the Tokyo Institute of Technology Leadership Award given to under only 5 students from undergraduate students in October 2016 because I was accepted activities inside and outside the school.
          <br>
          <br>
          After graduating from college, I conducted maintenance and operation of large-scale services and developed functions with a mid- and long-term perspective  at Recruit Co., Ltd.
          <br>
          <br>
          Currently I am in charge of general service development as CTO at OneBox Co., Ltd.
        </p>
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
  width: 8rem
  height: 8rem
  border-radius: 50%
  margin-bottom: 1rem

.profile__title
  font-size: 1.8rem
  font-weight: normal
  margin-bottom: .5rem
  color: #221D6D

.profile__subtitle
  font-size: 1.2rem
  font-weight: normal
  color: #221D6D

.profile__description-container
  background: #6D6D6D
  border: 1.2px solid #414536
  padding: 2rem
  border-radius: 8px 8px 50px 8px
  width: 80%
  margin: 2rem auto

.profile__description
  background: #8AB20F
  border: 1.2px solid #414536
  padding: 2rem
  border-radius: 2px
  font-size: .85rem
  text-align: left
</style>
