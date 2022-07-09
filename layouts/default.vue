<template class="daycycle-background">
  <div>
    <div class="daycycle-background" id="page_wrapper">
      <TheNavbar />
      <TheHeader />
    </div>
    <Nuxt />
    <TheFooter />
  </div>
</template>

<style scoped>
#page_wrapper {
  position: fixed;
  top: 0;
  height: 100%;
  overflow-y: scroll;
}
#page_wrapper {
  position: unset;
  overflow-y: unset;
}
</style>