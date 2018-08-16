<template>
    <div class="travel-wrap">
        <Travel_Bg/>
    </div>
</template>

<script>
  import Travel_Bg from '../components/Travel_Bg'

  export default {
    name: 'Travel',
    components: Travel_Bg,
  }
</script>

<style :lang="" scoped>
    .travel-wrap {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
    }
</style>
