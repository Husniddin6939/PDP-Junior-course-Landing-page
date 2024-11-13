<template>
    <header>
    <div class="container">
      <nav>
        <img src="../../assets/images/logo-removebg-preview.png" alt="logo"/>
        <ul>
          <li>Kurslarimiz</li>
          <li>Bog'lanish</li>
        </ul>
      </nav>
       <p><i class="bi bi-telephone-fill"></i>(78) 777-47-47</p>
    </div>
  </header>
</template>

<style lang="scss" scoped>
    header {
  background: rgb(0, 0, 0);
  background: linear-gradient(
    90deg,
    rgba(0, 0, 0, 1) 35%,
    rgba(0, 181, 52, 1) 100%
  );
  height: 64px;
  min-width:100vh ;
  padding: 8px 140px;

  .container{
    margin: 0 auto;
    padding:0 20px;
    box-sizing: border-box;
    display: flex;
    align-items: center;
    justify-content: space-between;

    nav{
      display: flex;
      align-items: center;
      &:first-child{
        gap: 33px;
      }

      ul{
        display: flex;
        gap: 22px;
        list-style-type: none;

        li{
          color: #88F036;
          font-size: 20px;
          font-weight: 400;
          line-height: 26px;
        }
      }
    }

    p{
      display: flex;
      align-items: center;
      gap: 12px;
      color: #fff;
      font-size: 20px;
      font-weight: 700;
      line-height: 26px;
    }


  }
}
</style>