<template>
  <div id="hy-swiper">
    <div class="swiper" >
      <slot></slot>
    </div>
    <slot name="indicator"></slot>
    <div class="indicator"></div>
  </div>
</template>

<script>
export default {
  name : 'Swiper',
}
</script>

<style>

</style>