<template>
  <footer>
    <div class="container">
      <div class="up">
        <img src="../../assets/images/logo-removebg-preview.png" alt="img" />
        <div class="socal">
          <img src="../../assets/images/tg.svg" alt="icon" />
          <img src="../../assets/images/insta.svg" alt="icon" />
          <img src="../../assets/images/you tube.svg" alt="icon" />
        </div>
        <p>(78) 777-47-47</p>
      </div>
      <div class="down">
        <p>©2022 PDP Academy</p>
        <span>Xizmatlar litsenziyalangan</span>
      </div>
    </div>
  </footer>
</template>

<script setup></script>

<style lang="scss" scoped>
footer {
  background-color: #012a30;
  padding:0 143px;

  .container {
    

    .up {
      padding: 22px 0;
      border-bottom: 1px solid #dbf9d8;
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 17px;

      .socal {
        display: flex;
        gap: 8px;
      }

      p {
        color: #ffff;
      }
    }

    .down{
        display: flex;
        align-items: center;
        justify-content: space-between;
        p{
            color: #ffff;
        }

        span{
            color: #ffff;
        }
    }
  }
}
</style>
