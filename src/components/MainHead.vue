<template>
  <div>
    <!-- <div class="hello">
      <h1>{{ msg }}</h1>
      <p>
        For a guide and recipes on how to configure / customize this project,<br />
        check out the
        <a href="https://cli.vuejs.org" target="_blank" rel="noopener"
          >vue-cli documentation</a
        >.
      </p>
      <h3>Installed CLI Plugins</h3>
      <ul>
        <li>
          <a
            href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel"
            target="_blank"
            rel="noopener"
            >babel</a
          >
        </li>
        <li>
          <a
            href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-router"
            target="_blank"
            rel="noopener"
            >router</a
          >
        </li>
        <li>
          <a
            href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-vuex"
            target="_blank"
            rel="noopener"
            >vuex</a
          >
        </li>
      </ul>
      <h3>Essential Links</h3>
      <ul>
        <li>
          <a href="https://vuejs.org" target="_blank" rel="noopener"
            >Core Docs</a
          >
        </li>
        <li>
          <a href="https://forum.vuejs.org" target="_blank" rel="noopener"
            >Forum</a
          >
        </li>
        <li>
          <a href="https://chat.vuejs.org" target="_blank" rel="noopener"
            >Community Chat</a
          >
        </li>
        <li>
          <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"
            >Twitter</a
          >
        </li>
        <li>
          <a href="https://news.vuejs.org" target="_blank" rel="noopener"
            >News</a
          >
        </li>
      </ul>
      <h3>Ecosystem</h3>
      <ul>
        <li>
          <a href="https://router.vuejs.org" target="_blank" rel="noopener"
            >vue-router</a
          >
        </li>
        <li>
          <a href="https://vuex.vuejs.org" target="_blank" rel="noopener"
            >vuex</a
          >
        </li>
        <li>
          <a
            href="https://github.com/vuejs/vue-devtools#vue-devtools"
            target="_blank"
            rel="noopener"
            >vue-devtools</a
          >
        </li>
        <li>
          <a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener"
            >vue-loader</a
          >
        </li>
        <li>
          <a
            href="https://github.com/vuejs/awesome-vue"
            target="_blank"
            rel="noopener"
            >awesome-vue</a
          >
        </li>
      </ul>
    </div> -->
    <main class="main-bg">
      <div class="header__main">
        <div class="main__picture">
          <div class="blue__round"></div>
          <!-- <div class="loader">
            <picture>
              <img class="main__img" src="../assets/mustang.png" alt="car" />
            </picture>
          </div> -->
          <button class="show-main__btn">
            <a href="/cars/">В Каталог</a>
          </button>
        </div>
        <div class="main__slogan">
          <h1 class="main__title">Приходи за <span>Мечтой</span>!</h1>
          <span class="main__text">
            <p>В нашем автосалоне огромный выбор автомобилей,</p>
            <p>на любой вкус и цвет,</p>
            <p>кто знает, может быть и Ваша мечта у нас?</p>
          </span>
          <p class="main__show">Кто знает, может быть Ваша мечта у нас?</p>
          <a class="main__btn" href="/cars/">В Каталог</a>
        </div>
      </div>
      <!-- <div class="section__form">
        <div class="buttons__container">
          <span class="span__show">Подбор новых авто онлайн</span>
          <form id="filter" class="select__form">
            <select
              class="filtered__select"
              id="filter--brand"
              name="filterBrand"
            >
              <option value="0">Марка</option>
            </select>
            <select
              id="filter--model"
              class="filtered__select"
              name="filterModel"
              disabled
            >
              <option value="0">Модель</option>
            </select>
            <div class="input__group">
              <input
                id="filter--min"
                class="filtered__input"
                type="number"
                inputmode="numeric"
                placeholder="Цена от"
              />
              <span></span>
              <input
                id="filter--max"
                class="filtered__input filtered__input_border"
                type="number"
                inputmode="numeric"
                placeholder="Цена до"
              />
            </div>
            <button id="filter--btn" class="filtered__btn" type="button">
              Найти
            </button>
          </form>

          <div class="display__none">
            <div class="top__form_buttons"></div>
          </div>
        </div>
      </div> -->
      <!-- <section class="offers">
        <div class="offers__row">
          <div class="offers__card offers__card1">
            <h5 class="offers__title">
              ГОСПРОГРАММА <br />Семейный автомобиль
            </h5>
            <a href="/goscredit/">
              <picture>
                <img src="/img/offer-arrow.png" alt="arrow" />
              </picture>
            </a>
          </div>
          <div class="offers__card offers__card2">
            <h5 class="offers__title">ГОСПРОГРАММА<br />Первый автомобиль</h5>
            <a href="/goscredit/">
              <picture>
                <img src="/img/offer-arrow.png" alt="arrow" />
              </picture>
            </a>
          </div>
          <div class="offers__card offers__card3">
            <h5 class="offers__title">ПРОГРАММА<br />Выгодный TRADE-IN</h5>
            <a href="/trade-in/">
              <picture>
                <img src="/img/offer-arrow.png" alt="arrow" />
              </picture>
            </a>
          </div>
          <div class="offers__card offers__card4">
            <h5 class="offers__title">Ставки по кредитам<br />от 4.9%</h5>
            <a href="/credit/">
              <picture>
                <img src="/img/offer-arrow.png" alt="arrow" />
              </picture>
            </a>
          </div>
        </div>
      </section> -->

      <!-- <section class="choose">
        <div class="choose__container">
          <div class="title">
            <h3 class="title__main">Горячее предложение!</h3>
            <p class="title__text">Выберите Свой Автомобиль</p>
          </div>
          <div class="choose__row">
            <CardHotOffer />
          </div>
        </div>
        <div class="main-bg pb">
          <button class="show__btn">Показать еще</button>
        </div>
      </section> -->
    </main>
  </div>
</template>

<script>
// import CardHotOffer from "@/components/CardHotOffer.vue";

export default {
  // name: "CardHotOffer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
main {
  background: darkseagreen;
}
.header__main {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  padding-top: 100px;
  background: url("../assets/mustang.png") no-repeat center left;
}
@media (max-width: 970px) {
  .header__main {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
  }
}
@media (max-width: 767px) {
  .header__main {
    padding: 0;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -ms-flex-direction: row;
    flex-direction: row;
    flex-direction: row-reverse;
    padding-bottom: 30px;
    padding-top: 100px;
  }
}
.header__main .main__picture {
  position: relative;
}
@media (max-width: 970px) {
  .header__main .main__picture {
    width: 536px;
    margin: 0 auto;
  }
}
@media (max-width: 767px) {
  .header__main .main__picture {
    overflow: hidden;
  }
}
@media (max-width: 640px) {
  .header__main .main__picture {
    width: 300px;
  }
}
@media (max-width: 375px) {
  .header__main .main__picture {
    width: 224px;
    height: 220px;
  }
}
.header__main .main__picture .blue__round {
  width: 414px;
  height: 414px;
  background-color: var(--blue-color);
  border-radius: 50%;
}
@media (max-width: 1076px) {
  .header__main .main__picture .blue__round {
    width: 350px;
    height: 350px;
  }
}
@media (max-width: 767px) {
  .header__main .main__picture .blue__round {
    position: relative;
    width: 300px;
    height: 300px;
    right: -120px;
  }
}
@media (max-width: 640px) {
  .header__main .main__picture .blue__round {
    width: 190px;
    height: 190px;
    top: 20px;
    right: -100px;
  }
}
@media (max-width: 540px) {
  .header__main .main__picture .blue__round {
    top: 0;
  }
}
@media (max-width: 375px) {
  .header__main .main__picture .blue__round {
    width: 153px;
    height: 153px;
    right: -100px;
  }
}
.header__main .main__picture .main__img {
  position: absolute;
  top: 0;
  left: 70px;
  width: 596px;
  height: 405px;
}
@media (max-width: 1076px) {
  .header__main .main__picture .main__img {
    width: 490px;
    height: 333px;
  }
}
@media (max-width: 767px) {
  .header__main .main__picture .main__img {
    width: 410px;
    height: 279px;
    top: 20px;
    left: 0;
    -webkit-transform: scale(-1, 1);
    -ms-transform: scale(-1, 1);
    transform: scale(-1, 1);
  }
}
@media (max-width: 640px) {
  .header__main .main__picture .main__img {
    width: 260px;
    height: 180px;
    top: 40px;
    left: 0;
  }
}
@media (max-width: 540px) {
  .header__main .main__picture .main__img {
    top: 20px;
  }
  .main-bg {
    overflow: hidden;
  }
}
@media (max-width: 375px) {
  .header__main .main__picture .main__img {
    width: 224px;
    height: 158px;
    top: 10px;
    left: 8px;
  }
}
.header__main .main__picture .show-main__btn {
  display: none;
  width: 148px;
  height: 34px;
  background: var(--blue-color);
  border-radius: 5px;
  font-weight: 700;
  font-size: 12px;
  line-height: 24px;
  color: #fcfdfd;
  -webkit-transition: all 0.3s ease;
  -o-transition: all 0.3s ease;
  transition: all 0.3s ease;
}
.header__main .main__picture .show-main__btn:hover {
  background: #fcfdfd;
  color: var(--blue-color);
  border: 1px solid var(--blue-color);
}
@media (max-width: 375px) {
  .header__main .main__picture .show-main__btn {
    display: block;
    position: absolute;
    bottom: 0;
    right: 10px;
  }
}
.header__main .main__slogan {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: end;
  -ms-flex-align: end;
  align-items: flex-end;
  margin: 53px 0 100px;
}
@media (max-width: 1076px) {
  .header__main .main__slogan {
    margin: 53px 0;
  }
}
@media (max-width: 970px) {
  .header__main .main__slogan {
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    min-height: 180px;
    margin: 20px 0;
  }
}
@media (max-width: 767px) {
  .header__main .main__slogan {
    -webkit-box-align: start;
    -ms-flex-align: start;
    align-items: flex-start;
    padding-left: 20px;
  }
}
@media (max-width: 540px) {
  .header__main .main__slogan {
    width: 260px;
    margin: 10px 0;
  }
}
@media (max-width: 375px) {
  .header__main .main__slogan {
    width: 190px;
    -webkit-box-pack: start;
    -ms-flex-pack: start;
    justify-content: flex-start;
    padding-left: 5px;
  }
}
.header__main .main__slogan .main__title {
  font-weight: 700;
  font-size: 48px;
  line-height: 54px;
  text-align: right;
}
@media (max-width: 1076px) {
  .header__main .main__slogan .main__title {
    font-size: 44px;
    line-height: 48px;
  }
}
@media (max-width: 970px) {
  .header__main .main__slogan .main__title {
    text-align: center;
  }
}
@media (max-width: 767px) {
  .header__main .main__slogan .main__title {
    text-align: left;
  }
}
@media (max-width: 640px) {
  .header__main .main__slogan .main__title {
    font-size: 30px;
    line-height: 34px;
  }
}
@media (max-width: 480px) {
  .header__main .main__slogan .main__title {
    font-size: 24px;
    line-height: 29px;
    width: 145px;
  }
}
@media (max-width: 375px) {
  .header__main .main__slogan .main__title {
    font-size: 22px;
    line-height: 29px;
  }
}
.header__main .main__slogan .main__title span {
  color: var(--blue-color);
  font-weight: 700;
}
.header__main .main__slogan .main__text {
  font-weight: 500;
  font-size: 14px;
  line-height: 21px;
  text-align: right;
  color: #747474;
}
@media (max-width: 1076px) {
  .header__main .main__slogan .main__text {
    line-height: 16px;
  }
}
@media (max-width: 970px) {
  .header__main .main__slogan .main__text {
    text-align: center;
  }
}
@media (max-width: 767px) {
  .header__main .main__slogan .main__text {
    text-align: left;
    width: 260px;
  }
}
@media (max-width: 640px) {
  .header__main .main__slogan .main__text {
    font-size: 14px;
    line-height: 16px;
  }
}
@media (max-width: 540px) {
  .header__main .main__slogan .main__text {
    display: none;
  }
}
.header__main .main__slogan .main__text p {
  padding: 3px 0;
}
.header__main .main__slogan .main__show {
  display: none;
}
@media (max-width: 540px) {
  .header__main .main__slogan .main__show {
    display: block;
    font-weight: 500;
    font-size: 12px;
    line-height: 18px;
    text-align: left;
    width: 140px;
  }
}
@media (max-width: 375px) {
  .header__main .main__slogan .main__show {
    margin-top: 20px;
  }
}
.header__main .main__slogan .main__btn {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  width: 191px;
  height: 35px;
  color: var(--white-color);
  background: var(--blue-color);
  border-radius: 5px;
  font-weight: 700;
  font-size: 12px;
  line-height: 24px;
  -webkit-transition: all 0.3s ease;
  -o-transition: all 0.3s ease;
  transition: all 0.3s ease;
}
.header__main .main__slogan .main__btn:hover {
  background: var(--white-color);
  color: var(--blue-color);
  border: 1px solid var(--blue-color);
}
@media (max-width: 540px) {
  .header__main .main__slogan .main__btn {
    width: 158px;
    height: 34px;
    margin-top: 10px;
  }
}
@media (max-width: 375px) {
  .header__main .main__slogan .main__btn {
    display: none;
  }
}
</style>
