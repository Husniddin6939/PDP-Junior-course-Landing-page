<template>
  <div class="card">
    <h1>PDP Junior – IT kelajakni shu yerdan boshlang!</h1>

    <div class="column">
      <div class="number">1</div>
      <div class="theme">
        <strong>Sifatli Ta’lim</strong>
        <p>
          5 yildan beri katta-yu kichik dasturchilarni <br />
          yetishtirib chiqarmoqda
        </p>
      </div>
    </div>

    <div class="column">
      <div class="number">2</div>
      <div class="theme">
        <strong>Bilim va ko'nikma</strong>
        <p>
          Yoshlar dasturlash va tanqidiy fikrlash <br />
          ko'nikmalariga ega bo'lishmoqda
        </p>
      </div>
    </div>

    <div class="column">
      <div class="number">3</div>
      <div class="theme">
        <strong>Natija</strong>
        <p>
          Algoritmlar orqali masalalar yechib, kichik <br />
          oʻyinlar yasashmoqda
        </p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.card {
  position: absolute;
  width: 403px;
  height: 396px;
  background-color: #ffff;
  top: 15px;
  left: 22px;
  padding: 13px 39px 53px 39px;

  h1 {
    font-size: 31px;
    font-weight: 800;
    line-height: 40px;
  }

  .column {
    display: flex;
    gap: 20px;

    .number {
      width: 45px;
      height: 45px;
      background-color: #dbf9d8;
      place-content: center;
      text-align: center;
      border-radius: 50%;
      font-size: 27px;
      font-weight: 800;
    }

    .theme {
      display: flex;
      flex-direction: column;

      strong {
        color: #00b534;
        font-size: 21px;
        font-weight: 800;
      }

      p {
        color: #012a30;
        font-size: 17px;
        font-weight: 400;
        line-height: 22px;
      }
    }
  }
}
</style>
