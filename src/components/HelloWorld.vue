<script setup>


</script>

<template>

  <div class="background-gif">
    <div class="animegirl">
      <img src="../assets/animegirl.jpg"  style="width: 30%; height: auto;" />
    </div>

    <div class="button-container">
      <button class="big-button">
        <a href="https://buy.stripe.com/aEUcOv0zsgcWbbafYY">GIMME YOUR MONEY</a>
      </button>
    </div>


    <div class="animegirl">
      <img src="../assets/azusamoney.gif"  style="width: 30%; height: auto;" />
    </div>
  </div>
  

  
</template>

<style scoped>
  .background-gif {
  background-image: url('../assets/money.gif');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  height: 100vh;
  width: 100vw;
  }

.button-container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.big-button {
  font-size: 30px;
  padding: 20px;
  width: 400px;
  height: 200px;
}

.animegirl {
  display: flex;
  justify-content: center;
  align-items: center;
  
}
#peterimage {
  position: fixed;
  bottom: 0;
}

</style>
