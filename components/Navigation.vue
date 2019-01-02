<template>
  <ul class="naviation">
    <li>
      <a
        href="/"
        class="navigation__item">
        Profile
      </a>
    </li>
    <li>
      <a
        href="/portfolio"
        class="navigation__item">
        Portfolio
      </a>
    </li>
    <li>
      <a
        href="https://www.tsurutan.com/"
        class="navigation__item"
        target="_blank">
        Blog
      </a>
    </li>
  </ul>
</template>

<style lang="sass">
.naviation
  position: fixed
  height: 100vh
  border-right: 1px solid #757575
  width: 10rem
  list-style: none
  padding: 0

.navigation__item
  display: block
  margin: 0
  padding: 1rem 3rem
  width: 100%
  text-decoration: none
  color: #757575
  &:hover
    background: #F5F5F5

</style>
