<template>
  <div class="page">
    <div class="page__layout">
      <div class="page__header">
        <div class="page__header-img"></div>
        <div class="page__header-h">PKT Bot Diamond</div>
        <div class="page__header-title">
          Поиск расписания по нескольким критериям, оповещения о грядущих
          занятиях и возможность поддержать разработчика бота
        </div>
      </div>

      <div class="page__features-list">
        <div class="feature">
          <div class="feature__icon">
            <svg class="icon" width="28" height="28" viewBox="0 0 28 28" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M3 11.3516C3 16.5078 7.19531 20.7031 12.3516 20.7031C14.3906 20.7031 16.2539 20.0469 17.7891 18.9453L23.5547 24.7227C23.8242 24.9922 24.1758 25.1211 24.5508 25.1211C25.3477 25.1211 25.8984 24.5234 25.8984 23.7383C25.8984 23.3633 25.7578 23.0234 25.5117 22.7773L19.7812 17.0117C20.9883 15.4414 21.7031 13.4844 21.7031 11.3516C21.7031 6.19531 17.5078 2 12.3516 2C7.19531 2 3 6.19531 3 11.3516ZM5.00391 11.3516C5.00391 7.29688 8.29688 4.00391 12.3516 4.00391C16.4062 4.00391 19.6992 7.29688 19.6992 11.3516C19.6992 15.4062 16.4062 18.6992 12.3516 18.6992C8.29688 18.6992 5.00391 15.4062 5.00391 11.3516Z" fill="white"/>
            </svg>
          </div>
          <div class="feature__header">Поиск</div>
          <div class="feature__title">
            Возможность искать расписание по нескольким
            критериям: по группе, преподавателю и аудитории
          </div>
        </div>
      </div>

      <div class="page__button-container">
        <button class="page__purchase-subscription-btn">
          Подключить за 49₽ в месяц
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "without-premium-page"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600&display=swap');

@font-face {
  font-family: 'Gilroy';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('../fonts/Gilroy-Regular.eot');
  src: local('Gilroy Regular'),
  local('Gilroy-Regular'),
  url('../fonts/Gilroy-Regular.eot?#iefix') format('embedded-opentype'),
  url('../fonts/Gilroy-Regular.woff') format('woff'),
  url('../fonts/Gilroy-Regular.ttf') format('truetype');
}

@font-face {
  font-family: 'Gilroy';
  font-weight: bold;
  font-style: normal;
  font-display: swap;
  src: url('../fonts/Gilroy-Bold.eot');
  src: local('Gilroy Bold'),
  local('Gilroy-Bold'),
  url('../fonts/Gilroy-Bold.eot?#iefix') format('embedded-opentype'),
  url('../fonts/Gilroy-Bold.woff') format('woff'),
  url('../fonts/Gilroy-Bold.ttf') format('truetype');
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Gilroy', sans-serif;
  font-weight: 400;
}

.page {
}

.page__layout {
  /*display: grid;*/
}

/* HEADER ------------------------------------------------------------------ */

.page__header {
  height: 235px;
  background-color: #756CD0;
  color: #FFFFFF;
  padding-top: 10px;
  padding-bottom: 10px;
}

/*.page_button-container {*/
/*  padding: 10px;*/
/*}*/

.page__header-img {
  display: block;
  margin: 0 auto;
}

.page__header-h {
  margin-top: 10px;
  font-size: 20px;
  text-align: center;
  font-weight: 600;
}

.page__header-title {
  margin-top: 5px;
  text-align: center;
  font-size: 14px;
}

/* FEATURES --------------------------------------------------------------- */

.page__features-list {
  overflow-y: hidden;
  padding-bottom: 50px;
  background-color: #FFFFFF;
}

.feature {
  display: flex;
  margin: 20px;
  align-content: stretch;
}

.feature__icon {
  min-width: 36px;
  width: 36px;
  height: 36px;
  background-color: #756CD0;
  border-radius: 15px;
}

.icon {
  display: block;
  margin: 5px auto;
  text-align: center;
}

hr {
  border: 1px solid #F2F2F7;
}

hr:last-child {
  border: none;
}

.feature__header {
  margin-left: 10px;
  font-size: 14px;
  font-weight: 400;
}

.feature__title {
  margin-top: 5px;
  font-size: 12px;
  font-weight: 400;
  color: #AEAEB2;
  display: inline-block;
  line-height: 12px;
}

/* FOOTER ----------------------------------------------------------------- */

.page__button-container {
  position: fixed;
  bottom: 0;
  height: 60px;
  width: 100vw;
  z-index: 3;
  background-color: #FFFFFF;
}

.page__purchase-subscription-btn {
  position: fixed;
  height: 40px;
  bottom: 10px;
  left: 20px;
  right: 20px;
  /*right: 30px;*/
  /*margin: 0 auto;*/
  /*text-align: center;*/
  /*transform: translate(-50%, -50%);*/

  background-color: #756CD0;
  color: #FFFFFF;
  border-radius: 15px;
  text-decoration: none;
  border: none;
}
</style>
