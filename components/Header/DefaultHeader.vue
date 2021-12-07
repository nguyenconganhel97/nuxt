<template>
  <header class="header">
    <ul>
      <li>
        <nuxt-link to="/decks"> Decks </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/articles"> Article </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/settings"> Settings </nuxt-link>
      </li>
    </ul>
  </header>
</template>
<style lang="scss" scoped>
.header {
  background: #000;
  color: #fff;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  ul {
    display: flex;
    align-items: center;
    justify-content: center;
    list-style: none;
    li {
      margin: 0 1rem;
      a {
        text-decoration: none;
        color: #fff;
        &:hover {
          text-decoration: underline;
        }
      }
    }
  }
}
</style>