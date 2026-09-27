<template>
  <div class="slide-number">
    {{ $slidev.nav.currentPage }}
  </div>
</template>

<style>
.slide-number {
  position: absolute;
  bottom: 20px;
  right: 30px;
  font-size: 14px;
  color: #334e68;
}
</style>
