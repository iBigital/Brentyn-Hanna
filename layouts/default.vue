<template class="daycycle-background">
  <main>
    <div class="daycycle-background" id="page_wrapper">
      <TheNavbar />
      <TheHeader />
    </div>
    <slot />
    <TheFooter />
  </main>
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