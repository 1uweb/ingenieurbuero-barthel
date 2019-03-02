<template>
  <div class="layout">
    <transition name="fade" appear>
      <main>
        <!-- a wrapper for slot is needed -->
        <slot/>
        <!-- the content -->
      </main>
    </transition>
  </div>
</template>

<style>
.fade-enter-active {
  transition: opacity 0.5s;
}

.fade-enter {
  opacity: 0;
}
</style>