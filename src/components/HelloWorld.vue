<script setup>


</script>

<template>

  <div class="background-gif">
    <div class="animegirl">
      <img src="../assets/animegirl.jpg"  style="width: 30%; height: auto;" />
    </div>

    <div class="button-container">
      <a href="https://buy.stripe.com/aEUcOv0zsgcWbbafYY" >
        <button class="big-button" >
            GIMME YOUR MONEY
        </button>
      </a>
    </div>


    <div class="animegirl">
      <img src="../assets/azusamoney.gif"  style="width: 30%; height: auto;" />
    </div>
  </div>
  
  <audio src="https://audio.jukehost.co.uk/VhdthnsCWpyah7f9augkrlFIxEk5S5Kc" controls autoplay style="display:none" ></audio>
  
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
  font-family: 'Courier New', Courier, monospace;
  color: purple;
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
