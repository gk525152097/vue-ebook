<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
document.addEventListener('DOMContentLoaded', () => {
  const html = document.querySelector('html')
  let fontSizeReset = window.innerWidth / 10
  fontSizeReset = fontSizeReset > 50 ? 50 : fontSizeReset
  html.style.fontSize = fontSizeReset + 'px'
})
</script>

<style lang="scss">

</style>
