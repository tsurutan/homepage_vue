<template>
  <div class="container">
    <div>
      <img
        class="profile__image"
        src="~/assets/image/designer-pic.png" >
      <h1 class="profile__title">
        Atsuhiro Tsuruta (鶴田 篤広)
      </h1>
      <h2 class="profile__subtitle">
        Engineer / UI UX Designer / Data Scientist
      </h2>
      <p class="profile__description">
        2013年東京工業大学に入学。Fablic, Coincheck,Translimit, FreakOut,Drivemode,MICIN,Redishにて長期インターンとして働き、Android アプリ、サーバー開発、データ解析を任される。 扶養がはずれないように現在は個人事業主として活動中。 大学ではレビュー文を扱った自然言語処理の研究を行う。 校内外での活動が認められ2016年10月に学部生から5名のみに与えられる東工大リーダーシップ賞を受賞する。 現在はリクルートにて大規模サービスの保守・運用、中長期を見据えた機能開発を行っている。
      </p>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style lang="sass">
.container
  display: flex
  justify-content: center
  text-align: center
  margin-left: 10rem
  padding: 4rem 0
  width: 100%

.profile__image
  width: 10rem
  height: 10rem
  border-radius: 50%
  margin-bottom: 1rem

.profile__title
  font-size: 1.8rem
  font-weight: normal
  margin-bottom: .5rem

.profile__subtitle
  font-size: 1.2rem
  font-weight: normal

.profile__description
  background: #F5F5F5
  padding: 2rem
  border-radius: 8px
  width: 80%
  text-align: left
  margin: 2rem auto
</style>
