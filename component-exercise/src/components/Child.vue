<template>
  <div class="place">
        <img :src="img" width="235" height="300"/>
         <slot></slot>
        <p>{{desc}}</p>
  </div>
</template>

<script>
export default {
   props: ["img", "desc"]
}
</script>

<style scoped>

</style>


