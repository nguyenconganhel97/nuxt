<template>
  <div>
    {{ $route.params.id }}
  </div>
</template>
<script>
export default {
  validate({ params }) {
    return /^[0-9]{9,12}/.test(params.id)
  },
}
</script>