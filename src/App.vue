<script setup lang="ts">
onLaunch(() => {
  console.log('App Launch')
})
onShow(() => {
  console.log('App Show')
})
onHide(() => {
  console.log('App Hide')
})

</script>

<style lang="scss">
@import 'tailwindcss/base';
@import 'tailwindcss/components';
@import 'tailwindcss/utilities';

uni-image {
  width: 100% !important;
  height: 100% !important;
}

image {
  width: 100% ;
  height: 100% ;
}

button::after {
  border: none !important;
}
</style>
