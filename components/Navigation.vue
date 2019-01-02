<template>
  <ul class="naviation">
    <li>
      <router-link
        to="/"
        class="navigation__item">
        Profile
      </router-link>
    </li>
    <li>
      <router-link
        to="/portfolio"
        class="navigation__item">
        Portfolio
      </router-link>
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
  width: 15rem
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
