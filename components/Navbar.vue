<template>
  <div class="promo">
    ⏰ OFFER ENDS SOON | ENTER TO WIN YOUR TRIP + €100 DISCOUNT | CODE:
    EARLY2024
  </div>
  <div class="logo">
    <div class="logo_name">WaveRoad</div>
    <div class="help">? <a href="">Help</a></div>
  </div>
</template>

<style>
.promo {
  background-color: #d2bfa3;
  text-align: center;
  height: 100%;
  width: 100%;
  font-weight: bold;
  font-size: 16px;
  padding-top: 8px;
  padding-bottom: 8px;

  @media screen and (max-width: 768px) {
    /* Adjust the font size for screens up to 768 pixels wide */
    font-size: 14px;
  }

  @media screen and (max-width: 576px) {
    /* Adjust the font size for screens up to 576 pixels wide */
    font-size: 12px;
  }
}
.logo {
  background-color: #6bbbae;
  text-align: center;
  height: 100%;
  width: 100%;
  font-weight: bold;
  font-family: Encode Sans;
  font-size: 16px;
  display: flex;
  justify-content: space-around;
  padding-top: 8px;
  padding-bottom: 8px;
}
.logo_name {
  color: white;
  font-size: 40px;

  @media screen and (max-width: 768px) {
    /* Adjust the font size for screens up to 768 pixels wide */
    font-size: 30px;
  }

  @media screen and (max-width: 576px) {
    /* Adjust the font size for screens up to 576 pixels wide */
    font-size: 20px;
  }
}
.help {
  align-self: center;
  text-decoration: none;
  line-height: 24px;
  letter-spacing: normal;
}
a:visited {
  text-decoration: none;
  color: black;
}
</style>
