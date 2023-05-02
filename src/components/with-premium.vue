<template>
  <div class="page">
    <div class="page__layout">

      <div class="page__top-bar top-bar">
        <!--        <div class="top-bar__icon">-->
        <!--          <img src="https://img.icons8.com/external-flatart-icons-lineal-color-flatarticons/32/null/external-premium-seo-flatart-icons-lineal-color-flatarticons.png"/>-->
        <!--        </div>-->
        <p class="top-bar__title">PKT Bot Diamond</p>
      </div>

      <ul class="settings__list">
        <li class="settings__item block">
          <h6 class="block__title">Отображение расписания</h6>
          <p class="block__description">
            Настроить формат сообщений с расписанием занятий.
            Например, сократить названия и имена
          </p>
          <ul class="block__list">
            <li class="block__item item">
              <p class="item__title">Сократить названия предметов</p>
              <label class="form-switch">
                <input type="checkbox">
                <i></i>
              </label>
            </li>
            <li class="block__item item remove-line">
              <p class="item__title">Сократить имена учителей</p>
              <label class="form-switch">
                <input type="checkbox">
                <i></i>
              </label>
            </li>
          </ul>
        </li>

        <li class="settings__item block">
          <h6 class="block__title">Мультигруппы</h6>
          <p class="block__description">
            При добавлении группы появится дополнительная кнопка,
            которая позволит смотреть расписание для этой группы
          </p>
          <button class="sblock">
            <svg class="sblock__icon" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M8 15.9921C12.3765 15.9921 16 12.3626 16 7.99605C16 3.62175 12.3687 0 7.99217 0C3.62354 0 0 3.62175 0 7.99605C0 12.3626 3.63138 15.9921 8 15.9921ZM8 14.6595C4.29805 14.6595 1.34118 11.6962 1.34118 7.99605C1.34118 4.29593 4.29021 1.33268 7.99217 1.33268C11.6942 1.33268 14.6667 4.29593 14.6667 7.99605C14.6667 11.6962 11.702 14.6595 8 14.6595ZM4.36079 7.99605C4.36079 8.38017 4.62746 8.63892 5.02746 8.63892H7.33333V10.9515C7.33333 11.3434 7.60004 11.6178 7.98434 11.6178C8.37647 11.6178 8.65101 11.3513 8.65101 10.9515V8.63892H10.9647C11.3569 8.63892 11.6314 8.38017 11.6314 7.99605C11.6314 7.60411 11.3569 7.32971 10.9647 7.32971H8.65101V5.02498C8.65101 4.62518 8.37647 4.35081 7.98434 4.35081C7.60004 4.35081 7.33333 4.62518 7.33333 5.02498V7.32971H5.02746C4.62746 7.32971 4.36079 7.60411 4.36079 7.99605Z" fill="#756CD0"/>
            </svg>
            <p class="sblock__title">Добавить группу</p>
          </button>
        </li>

        <li class="settings__item block">
          <h6 class="block__title">Черный список</h6>
          <p class="block__description">
            При добавлении в этот список в расписании не будет выводиться
            добавленный преподаватель или предмет
          </p>
          <button class="sblock">
            <svg class="sblock__icon" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M8 15.9921C12.3765 15.9921 16 12.3626 16 7.99605C16 3.62175 12.3687 0 7.99217 0C3.62354 0 0 3.62175 0 7.99605C0 12.3626 3.63138 15.9921 8 15.9921ZM8 14.6595C4.29805 14.6595 1.34118 11.6962 1.34118 7.99605C1.34118 4.29593 4.29021 1.33268 7.99217 1.33268C11.6942 1.33268 14.6667 4.29593 14.6667 7.99605C14.6667 11.6962 11.702 14.6595 8 14.6595ZM4.36079 7.99605C4.36079 8.38017 4.62746 8.63892 5.02746 8.63892H7.33333V10.9515C7.33333 11.3434 7.60004 11.6178 7.98434 11.6178C8.37647 11.6178 8.65101 11.3513 8.65101 10.9515V8.63892H10.9647C11.3569 8.63892 11.6314 8.38017 11.6314 7.99605C11.6314 7.60411 11.3569 7.32971 10.9647 7.32971H8.65101V5.02498C8.65101 4.62518 8.37647 4.35081 7.98434 4.35081C7.60004 4.35081 7.33333 4.62518 7.33333 5.02498V7.32971H5.02746C4.62746 7.32971 4.36079 7.60411 4.36079 7.99605Z" fill="#756CD0"/>
            </svg>
            <p class="sblock__title">Добавить</p>
          </button>
        </li>

        <li class="settings__item block">
          <h6 class="block__title">Оповещения</h6>
          <p class="block__description">
            При включении этой опции, бот будет каждый день отправлять
            расписание занятий. Также, вы можете настроить получение
            расписания: получать оповещение перед занятием, или вечером
          </p>
          <ul class="block__list">
            <li class="block__item item">
              <p class="item__title">Сократить названия предметов</p>
              <label class="form-switch">
                <input type="checkbox">
                <i></i>
              </label>
            </li>
            <li class="block__item item remove-line">
              <p class="item__title">Сократить имена учителей</p>
              <label class="form-switch">
                <input type="checkbox">
                <i></i>
              </label>
            </li>
          </ul>
        </li>
      </ul>

      <div class="footer">
        <div class="footer__list">
          <button class="sblock footer__item">
            <svg width="16" height="17" viewBox="0 0 16 17" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M0 9.2378C0 13.4842 3.63138 17 8 17C12.3765 17 16 13.4842 16 9.2378C16 5.49369 13.1843 2.32031 9.51372 1.62019V0.539567C9.51372 -0.000743707 9.12941 -0.145334 8.70589 0.151457L6.20393 1.84849C5.84315 2.09201 5.83531 2.45729 6.20393 2.70842L8.69806 4.41306C9.12941 4.71747 9.51372 4.57287 9.51372 4.02495V2.94433C12.4784 3.59879 14.6588 6.15576 14.6588 9.2378C14.6588 12.8298 11.702 15.7064 8 15.7064C4.29805 15.7064 1.32549 12.8298 1.33334 9.2378C1.34118 7.07657 2.42353 5.16646 4.09413 4.00974C4.4157 3.77382 4.51766 3.41615 4.32158 3.09653C4.1255 2.78452 3.69412 2.70081 3.34903 2.95955C1.33334 4.38262 0 6.68084 0 9.2378Z" fill="#756CD0"/>
            </svg>

            <p class="sblock__title">Сбросить настройки</p>
          </button>
          <button class="sblock footer__item">
            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4.46461 16C4.82033 16 5.06716 15.7989 5.50999 15.3813L8.01453 13.0072H12.6751C14.8385 13.0072 16 11.7312 16 9.46547V3.54181C16 1.27598 14.8385 0 12.6751 0H3.32487C1.16153 0 0 1.26825 0 3.54181V9.46547C0 11.739 1.16153 13.0072 3.32487 13.0072H3.67333V15.0179C3.67333 15.6134 3.95645 16 4.46461 16ZM4.76225 14.5848V12.3422C4.76225 11.9246 4.60981 11.7622 4.21779 11.7622H3.32487C1.85844 11.7622 1.16879 10.9657 1.16879 9.45769V3.54181C1.16879 2.03383 1.85844 1.24505 3.32487 1.24505H12.6751C14.1343 1.24505 14.8312 2.03383 14.8312 3.54181V9.45769C14.8312 10.9657 14.1343 11.7622 12.6751 11.7622H7.97098C7.56441 11.7622 7.36116 11.8241 7.08531 12.1257L4.76225 14.5848ZM7.86207 8.10436C8.22503 8.10436 8.44283 7.8569 8.44283 7.55533C8.44283 7.52438 8.44283 7.48577 8.44283 7.46254C8.44283 7.02945 8.68239 6.75111 9.19055 6.39535C9.89477 5.90043 10.3956 5.45191 10.3956 4.52392C10.3956 3.24021 9.32126 2.55196 8.08713 2.55196C6.83851 2.55196 6.01815 3.17835 5.81489 3.8898C5.77859 4.01353 5.75681 4.13726 5.75681 4.26873C5.75681 4.61672 6.01089 4.80232 6.25774 4.80232C6.50454 4.80232 6.657 4.67859 6.78765 4.49299L6.91836 4.30739C7.17241 3.85887 7.55716 3.59594 8.03633 3.59594C8.70419 3.59594 9.1325 3.99806 9.1325 4.58579C9.1325 5.11164 8.82759 5.36684 8.18879 5.8386C7.67332 6.22523 7.28131 6.6351 7.28131 7.39293C7.28131 7.42387 7.28131 7.46254 7.28131 7.49349C7.28131 7.89557 7.48456 8.10436 7.86207 8.10436ZM7.84027 10.4089C8.26133 10.4089 8.62434 10.0609 8.62434 9.60465C8.62434 9.15611 8.26864 8.80815 7.84027 8.80815C7.41927 8.80815 7.0635 9.16383 7.0635 9.60465C7.0635 10.0532 7.42652 10.4089 7.84027 10.4089Z" fill="#756CD0"/>
            </svg>

            <p class="sblock__title">Написать в техподдержку</p>
          </button>
        </div>
      </div>

    </div>
  </div>
</template>

<script>
</script>

<style>
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

@font-face {
  font-family: 'Gilroy';
  src: url('../fonts/Gilroy-SemiBold.eot');
  src: local('Gilroy SemiBold'), local('Gilroy-SemiBold'),
  url('../fonts/Gilroy-SemiBold.eot?#iefix') format('embedded-opentype'),
  url('../fonts/Gilroy-SemiBold.woff') format('woff'),
  url('../fonts/Gilroy-SemiBold.ttf') format('truetype');
  font-weight: 600;
  font-style: normal;
}

@font-face {
  font-family: 'Gilroy';
  src: url('../fonts/Gilroy-Medium.eot');
  src: local('Gilroy Medium'), local('Gilroy-Medium'),
  url('../fonts/Gilroy-Medium.eot?#iefix') format('embedded-opentype'),
  url('../fonts/Gilroy-Medium.woff') format('woff'),
  url('../fonts/Gilroy-Medium.ttf') format('truetype');
  font-weight: 500;
  font-style: normal;
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

button{
  cursor: pointer;
}

.top-bar {
  position: sticky;
  top: 0px;
  display: flex;
  align-items: center;
  height: 50px;
  background-color: #756CD0;
  color: #FFFFFF;
  z-index: 2;
}

.top-bar__icon {
  margin-left: 15px;
}

.top-bar__title {
  font-weight: 500;
  margin-left: 15px;
}

.block:first-child {
  margin-top: 15px;
}

.block {
  margin-left: 15px;
  margin-right: 15px;
  margin-top: 30px;
  list-style-type: none;
}

.block__title {
  font-size: 20px;
  font-weight: 600;
}

.block__description {
  border-width: 1px;
  border-color: #F2F2F7;
  border-style: solid;
  border-left: none;
  border-right: none;
  border-top: none;

  margin-top: 10px;
  padding-bottom: 10px;
  font-size: 14px;
  font-weight: 400;
  color: #AEAEB2;
}

.block__list {
  margin-top: 10px;
  list-style-type: none;
  font-size: 14px;
  font-weight: 400;
}

.item {
  padding-bottom: 10px;
  margin-bottom: 10px;
  border-width: 1px;
  border-color: #F2F2F7;
  border-style: solid;
  border-left: none;
  border-right: none;
  border-top: none;

  display: flex;
  align-items: center;
  justify-content: space-between;
}

.item__title {
  margin-right: 10px;
}

.form-switch {
  display: inline-block;
  cursor: pointer;
  -webkit-tap-highlight-color: transparent;
}

.form-switch i {
  position: relative;
  display: inline-block;
  /*margin-right: .5rem;*/
  width: 26px;
  height: 16px;
  background-color: #e6e6e6;
  border-radius: 15px;
  vertical-align: text-bottom;
  transition: all 0.3s linear;
}

/*.form-switch i::before {*/
/*  content: "";*/
/*  position: absolute;*/
/*  left: 0;*/
/*  width: 22px;*/
/*  height: 12px;*/
/*  !*background-color: #AEAEB2;*!*/
/*  border-radius: 15px;*/
/*  transform: translate3d(2px, 2px, 0) scale3d(1, 1, 1);*/
/*  transition: all 0.1s linear;*/
/*}*/

/* !!! */
.form-switch i::after {
  content: "";
  position: absolute;
  left: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
  border-radius: 15px;
  /*box-shadow: 0 2px 2px rgba(0, 0, 0, 0.24);*/
  transform: translate3d(2px, 2px, 0);
  transition: all 0.3s linear;
}

.form-switch:active i::after {
  width: 18px;
  transform: translate3d(2px, 2px, 0);
}

.form-switch:active input:checked ~ i::after { transform: translate3d(16px, 2px, 0); }
.form-switch input[type=checkbox] { display: none; }
.form-switch input[type=checkbox]:checked ~ i { background-color: #4BD763; }
.form-switch input[type=checkbox]:checked ~ i::before { transform: translate3d(2px, 2px, 0) scale3d(0, 0, 0); }

.form-switch input[type=checkbox]:checked ~ i::after { transform: translate3d(12px, 2px, 0); }

.remove-line {
  border: none;
  margin-bottom: 0;
  padding-bottom: 0;
}

.sblock {
  display: flex;
  margin-top: 10px;
  align-items: center;
  border: none;
  background-color: #FFFFFF;
  font-size: 14px;
  text-decoration: none;
}

.sblock__icon {
  color: #756CD0;
}

.sblock__title {
  color: #756CD0;
  margin-left: 10px;
}

/*.item:last-child {*/
/*  border: none;*/
/*}*/

.footer__item {
  margin-left: 15px;
}

.footer__item:first-child {
  margin-top: 30px;
  padding-bottom: 10px;
  margin-bottom: 10px;
  border-width: 1px;
  border-color: #F2F2F7;
  border-style: solid;
  border-left: none;
  border-right: none;
  border-top: none;
}

.footer__item:last-child {
  margin-bottom: 30px;
}

</style>

