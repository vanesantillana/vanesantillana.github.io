<template>
  <div class="container">
    <div class="head">
      <div class="item">
        <span><i class=""></i> vanessasantillana59@gmail.com</span>
      </div>
      <div class="item">
        <span><i class=""></i> 918 527 596</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.head {
  display: flex;
  align-items: flex-start;
  justify-content: right;
}
</style>
