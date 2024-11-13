<template>
    <main>
    <section class="intro">
      <div class="container">
        <div class="wrapper">
          <div class="left">
            <img src="../../assets/images/backCard.png" alt="img">
            <Card/>

            

        </div>
        </div>
      </div>
    
    </section>
  </main>
</template>

<script setup>
import Card from "../card/index.vue";
</script>

<style lang="scss" scoped>
    .intro{
    width: 100%;
    height:100vh;
    background-image:url("../../assets/images/Vector.png");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;

    .wrapper{
      padding: 116px 141px;

      .left{
        position: relative;

        
      }
    }

  }
</style>