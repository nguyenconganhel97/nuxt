<template>
  <div class="page">
    <div class="nav">
      <ul>
        <li>
          <nuxt-link to="/settings"> General </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/settings/decks"> Decks </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/settings/schedule"> Schedule </nuxt-link>
        </li>
      </ul>
    </div>
    <nuxt-child />
  </div>
</template>
<script>
export default {}
</script>
<style lang="scss">
.page {
  display: flex;
}
</style>