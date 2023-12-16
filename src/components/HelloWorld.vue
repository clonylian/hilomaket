<template>
  <div class="hello">
      <div class="box">
          <div class="cent">
              <img src="../assets/10.png">
          </div> 
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
.cent{
  width: 100%;
  height: 80vh;
  color: white;
  background-image: url('../assets/1.png');
}
</style>
