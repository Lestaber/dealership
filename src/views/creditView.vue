<template>
    <div class="main-bg">
      <div class="title">
        <h3 class="title__main">Подать заявку на автокредит онлайн</h3>
        <p class="title__text"></p>
      </div>
    </div>
    <section class="credit__main">
      <div class="credit__container">
        <form class="credit__form" action="#" name="form" method="default-src">
          <h3>Узнайте решение за 30 минут</h3>
          <select name="" id="">
            <option value="">Марка</option>
          </select>
          <select name="" id="">
            <option value="">Модель</option>
          </select>
          <select name="" id="">
            <option value="">Комплектация</option>
          </select>
          <select name="" id="">
            <option value="">Цвет</option>
          </select>

          <!-- nouiSlider -->
          <div class="range__name">
            <div class="range__title">Первоначальный взнос</div>
            <span class="range__value" id="span-value"></span>
          </div>
          <div id="range"></div>
          <p class="range__text">*Скидка действует при первом взносе от 10%</p>
          <div class="range__name">
            <div class="range__title">Срок кредитования</div>
            <span class="range__value" id="span-value2"></span>
          </div>
          <div id="range2"></div>
          <!-- End -->

          <label class="credit__label" for="username">Ваше имя
            <input type="text" name="name" id="name" minlength="2" maxlength="20" data-reg="^[а-яА-ЯёЁa-zA-Z]*$"
              required>
          </label>
          <label class="credit__label" for="phone">Телефон
            <input type="text" name="phone" id="phone" data-reg="^((8|\+7)[\- ]?)?(\(?\d{3}\)?[\- ]?)?[\d\- ]{9}$"
              placeholder="+7..." required>
          </label>

          <div class="checkbox__block">
            <div class="checkbox">
              <input type="checkbox" value="None" id="checkbox" name="check" checked />
              <label for="checkbox" class="custom__label"></label>
            </div>
            <p>согласие на <a href="">обработку персональных данных*</a></p>
          </div>
          <div class="blue__form_button">
            <button class="blue__form_btn" type="submit">Отправить Заявку</button>
            <p class="blue__form_explain">*Кредит предоставляется только гражданам РФ</p>
          </div>
        </form>
        <div class="credit__content">
          <!--  Скрытый блок -->
          <div class="credit__car">
            <div class="credit__car-left">
              <h3>KIA Stinger</h3>
              <div>Цена со скидкой<span>2 309 900 ₽</span></div>
              <div>Ежемесячный платеж<span>от 42 939 ₽</span></div>
              <div>Ваша выгода<span>5 000 ₽</span></div>
              <div>
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <circle cx="10" cy="10" r="8.5" fill="white" stroke="#1E7EFF" stroke-width="3" />
                  <line y1="-1.5" x2="7.69961" y2="-1.5"
                    transform="matrix(-0.707107 0.707107 0.707107 0.707107 17 6.88892)" stroke="#454546"
                    stroke-width="3" />
                  <line y1="-1.5" x2="7.69961" y2="-1.5"
                    transform="matrix(0.707107 0.707107 0.707107 -0.707107 6.11084 6.88892)" stroke="#454546"
                    stroke-width="3" />
                </svg>
                <p>Trade-IN</p>
                <span>1500 ₽</span>
              </div>
              <div>
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <circle cx="10" cy="10" r="8.5" fill="white" stroke="#1E7EFF" stroke-width="3" />
                  <line y1="-1.5" x2="7.69961" y2="-1.5"
                    transform="matrix(-0.707107 0.707107 0.707107 0.707107 17 6.88892)" stroke="#454546"
                    stroke-width="3" />
                  <line y1="-1.5" x2="7.69961" y2="-1.5"
                    transform="matrix(0.707107 0.707107 0.707107 -0.707107 6.11084 6.88892)" stroke="#454546"
                    stroke-width="3" />
                </svg>
                <p>Госпрограммы</p>
                <span>1000 ₽</span>
              </div>
            </div>
            <div class="credit__car-img">
              <picture>
                <!-- <source srcset="./img/credit1.webp" type="image/webp"><img src="./img/credit1.png" alt="car"> -->
              </picture>
            </div>
          </div>
          <h3 class="privilege__title">Преимущества</h3>
          <div class="credit__privilege">
            <div>Первоначальный взнос от 0 руб</div>
            <div>Срок кредитования от 6 месяцев до 7 лет</div>
            <div>Возможность сдать свой автомобиль по системе Trade-in в качестве первоначального взноса</div>
            <div>Сумма кредитования до 3 000 000 руб</div>
            <div>Досрочное погашение без штрафов и комиссий</div>
            <div>Процентная ставка по кредитам от 1.9%</div>
          </div>
          <h3 class="privilege__title">Образцы кредитного договора</h3>
          <div class="credit__docs">
            <a href="#">
              <picture>
                <!-- <source srcset="./img/PDF.webp" type="image/webp"><img src="./img/PDF.png" alt="pdf"> -->
              </picture>
            </a>
            <a href="#">
              <picture>
                <!-- <source srcset="./img/PDF.webp" type="image/webp"><img src="./img/PDF.png" alt="pdf"> -->
              </picture>
            </a>
            <a href="#">
              <picture>
                <!-- <source srcset="./img/DOC.webp" type="image/webp"><img src="./img/DOC.png" alt="doc"> -->
              </picture>
            </a>
          </div>
          <div class="credit__descriotion">
            <div class="credit__col">
              <div class="credit__row">
                <picture>
                  <!-- <source srcset="./img/credit-people.webp" type="image/webp"><img src="./img/credit-people.png"
                    alt="people"> -->
                </picture>
                <h3>10 ЛЕТ РАБОТЫ<br>2 853 КЛИЕНТОВ</h3>
              </div>
              <div class="credit__row">
                <picture>
                  <!-- <source srcset="./img/credit-badge.webp" type="image/webp"><img src="./img/credit-badge.png"
                    alt="bage"> -->
                </picture>
                <h3>СКИДКИ И ПОДАРКИ<br>
                  ВСЕМ ПОКУПАТЕЛЯМ</h3>
              </div>
              <div class="credit__row">
                <picture>
                  <!-- <source srcset="./img/credit-sales.webp" type="image/webp"><img src="./img/credit-sales.png"
                    alt="sales"> -->
                </picture>
                <h3>ВСЕ АВТОМОБИЛИ<br>В НАЛИЧИИ И С ПТС</h3>
              </div>
              <div class="credit__row">
                <picture>
                  <!-- <source srcset="./img/credit-car.webp" type="image/webp"><img src="./img/credit-car.png"
                    alt="car-sale"> -->
                </picture>
                <h3>КРЕДИТ ОТ 1.9%<br>НА ВСЕ АВТОМОБИЛИ</h3>
              </div>
            </div>
          </div>
          <p class="credit__text">
            Выгодно ли оформлять кредит при приобретении автомобиля? Это зависит от условий банка, предоставляющего
            услугу кредитования. Автосалон «Независимость» имеет 18 банков-партнеров, благодаря чему мы подберем для Вас
            тот банк, условия которого полностью удовлетворят Ваши ожидания.
          </p>
          <p class="credit__text">
            Какие преимущества у автокредитования в автосалоне «Независимость»? Во-первых, Вы получите лояльную
            процентную ставку, которая стартует от 1,9% годовых. Во-вторых, Вам одобрят автокредит с вероятностью 95%.
            Наш кредитный отдел помогает каждому клиенту. В-третьих, Вам не нужно будет платить никаких комиссий и
            штрафов за досрочное погашение. Оно приветствуется. В-четвертых, Вам необязательно вносить сумму
            первоначального взноса, так как мы предлагаем своим клиентам взять данную сумму в беспроцентную рассрочку.
            Наконец, Вам обеспечена скидка не менее 17% от стоимости любой модели. Также данная скидка может быть
            увеличена за счет использования услуги Trade-In. Но бывают случаи, когда автолюбители только по приезду в
            автосалон понимают, что данное приобретение им не по карману.
          </p>
          <p class="credit__text">
            Поэтому в целях экономии Вашего времени на нашем сайте доступна такая функция, как «Калькулятор онлайн».
            Помимо того, что данная программа посчитает ориентировочную стоимость любого автомобиля, она позволяет
            рассчитать условия кредитования, а также через нее Вы можете оставить заявку на автокредит, после чего в
            течение 30 минут с Вами свяжется менеджер кредитного отдела, чтобы предоставить бесплатную консультацию.
          </p>
        </div>
      </div>
    </section>
    <div v-for="car in cars" :key="car.id">
       <p>{{car.title}}</p>
       <p>{{car.author}}</p>
       <img :src="car.img" alt="">
       <img src="" alt="">
    </div>
</template>
<script>
   import axios from "axios"
export default {

    data:() => ({
       cars:[]
    }),
    created(){
       axios.get('http://localhost:3000/cars')
       .then(response=>{
         this.cars = response.data
         console.log(response.data)
       })
       .catch(e=>{
          console.log('error' + e)
       })
    },

}
</script>
<style  scoped>

 .credit__main {
  min-height: 880px;
  background: var(--bg-main-color);
  padding: 20px;
}
@media (max-width: 460px) {
  .credit__main {
    padding: 0 10px;
  }
}
.credit__main .credit__container {
  max-width: 1160px;
  min-height: 800px;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  padding: 0 20px;
}
@media (max-width: 1199px) {
  .credit__main .credit__container {
    flex-direction: column;
    align-items: center;
  }
}
@media (max-width: 460px) {
  .credit__main .credit__container {
    padding: 0;
  }
}
.credit__main .credit__container .credit__form {
  width: 443px;
  min-height: 740px;
  background: var(--blue-color);
  padding: 0 45px;
  border-radius: 10px;
}
@media (max-width: 460px) {
  .credit__main .credit__container .credit__form {
    max-width: 400px;
    width: 100%;
    padding: 20px;
  }
}
.credit__main .credit__container .credit__form h3 {
  font-weight: 700;
  font-size: 20px;
  line-height: 20px;
  text-align: center;
  color: var(--white-color);
  margin: 35px 0;
}
.credit__main .credit__container .credit__form select {
  width: 353px;
  height: 34px;
  background: var(--white-color);
  box-shadow: 0px 0px 22px rgba(174, 193, 207, 0.3);
  border-radius: 5px;
  margin-bottom: 11px;
  font-weight: 700;
  font-size: 12px;
  line-height: 24px;
  color: #666666;
  padding: 0 20px;
}
@media (max-width: 490px) {
  .credit__main .credit__container .credit__form select {
    width: 100%;
  }
}
.credit__main .credit__container .credit__form #range2 {
  margin-bottom: 40px;
}
.credit__main .credit__container .credit__form .range__name {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 15px;
}
.credit__main .credit__container .credit__form .range__name .range__title {
  font-weight: 700;
  font-size: 12px;
  line-height: 14px;
  color: var(--white-color);
}
.credit__main .credit__container .credit__form .range__name .range__value {
  font-weight: 700;
  font-size: 12px;
  line-height: 14px;
  color: var(--white-color);
}
.credit__main .credit__container .credit__form .range__text {
  font-size: 9px;
  line-height: 200%;
  color: var(--white-color);
  margin-left: 20px;
}
.credit__main .credit__container .credit__form .credit__label {
  font-weight: 700;
  font-size: 12px;
  line-height: 12px;
  color: #f6f6f6;
  margin-left: 25px;
}
.credit__main .credit__container .credit__form input {
  width: 355px;
  height: 34px;
  background: var(--white-color);
  box-shadow: 0px 0px 22px rgba(174, 193, 207, 0.3);
  border-radius: 5px;
  margin-bottom: 11px;
  padding: 0 20px;
  margin-top: 5px;
}
@media (max-width: 490px) {
  .credit__main .credit__container .credit__form input {
    width: 100%;
  }
}
.credit__main .credit__container .credit__form .blue__form_button {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}
.credit__main .credit__container .credit__form .blue__form_button .blue__form_btn {
  width: 230px;
  height: 44px;
  font-weight: 700;
  font-size: 12px;
  line-height: 24px;
  border-radius: 5px;
  box-shadow: var(--box-shadow);
  background: var(--white-color);
  color: var(--blue-color);
  margin: 8px 0 4px;
  transition: all 0.4s ease;
}
@media (max-width: 490px) {
  .credit__main .credit__container .credit__form .blue__form_button .blue__form_btn {
    width: 100%;
  }
}
.credit__main .credit__container .credit__form .blue__form_button .blue__form_btn:hover {
  background: var(--blue-color);
  color: var(--white-color);
  border: 1px solid var(--white-color);
}
.credit__main .credit__container .credit__form .blue__form_button p {
  font-weight: 500;
  font-size: 9px;
  line-height: 18px;
  color: var(--white-color);
}
.credit__main .credit__container .credit__content {
  background: var(--white-color);
  border-radius: 10px;
  width: 717px;
  padding: 35px 70px 0 50px;
}
@media (max-width: 767px) {
  .credit__main .credit__container .credit__content {
    max-width: 717px;
    width: 100%;
    padding: 30px;
  }
}
@media (max-width: 700px) {
  .credit__main .credit__container .credit__content {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
}
@media (max-width: 520px) {
  .credit__main .credit__container .credit__content {
    max-width: 450px;
    width: 100%;
    padding: 20px;
  }
}
.credit__main .credit__container .credit__content .credit__car {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
@media (max-width: 700px) {
  .credit__main .credit__container .credit__content .credit__car {
    flex-direction: column-reverse;
    justify-content: center;
  }
}
.credit__main .credit__container .credit__content .credit__car .credit__car-left h3 {
  font-weight: 700;
  font-size: 18px;
  line-height: 36px;
}
.credit__main .credit__container .credit__content .credit__car .credit__car-left div {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 12px;
  line-height: 24px;
  color: var(--main-color);
  width: 230px;
}
.credit__main .credit__container .credit__content .credit__car .credit__car-left div p {
  font-size: 12px;
  line-height: 24px;
  color: var(--main-color);
  margin-right: 50px;
  width: 100px;
}
.credit__main .credit__container .credit__content .credit__car .credit__car-left div span {
  font-weight: 700;
  font-size: 12px;
  line-height: 24px;
  color: var(--blue-color);
  text-align: right;
}
.credit__main .credit__container .credit__content .credit__car .credit__car-img {
  margin-top: 30px;
}
@media (max-width: 700px) {
  .credit__main .credit__container .credit__content .credit__car .credit__car-img {
    margin: 0;
  }
}
@media (max-width: 460px) {
  .credit__main .credit__container .credit__content .credit__car .credit__car-img {
    display: none;
  }
}
.credit__main .credit__container .credit__content .privilege__title {
  margin-top: 20px;
  margin-bottom: 17px;
  font-weight: 700;
  font-size: 18px;
  line-height: 21px;
}
@media (max-width: 375px) {
  .credit__main .credit__container .credit__content .privilege__title {
    font-size: 15px;
    line-height: 10px;
  }
}
.credit__main .credit__container .credit__content .credit__privilege {
  -moz-columns: 2;
       columns: 2;
  -moz-column-gap: 72px;
       column-gap: 72px;
  margin-left: -5px;
}
@media (max-width: 700px) {
  .credit__main .credit__container .credit__content .credit__privilege {
    -moz-columns: 1;
         columns: 1;
    margin: 0;
  }
}
.credit__main .credit__container .credit__content .credit__privilege div {
  font-size: 11px;
  line-height: 16px;
  position: relative;
  padding-left: 22px;
  margin-bottom: 15px;
  width: 262px;
}
.credit__main .credit__container .credit__content .credit__privilege div:nth-child(3) {
  width: 304px;
}
@media (max-width: 375px) {
  .credit__main .credit__container .credit__content .credit__privilege div:nth-child(3) {
    width: auto;
  }
}
.credit__main .credit__container .credit__content .credit__privilege div::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 14px;
  height: 14px;
  background: linear-gradient(var(--blue-color), var(--blue-color)), linear-gradient(var(--blue-color), var(--blue-color));
  background-position: center;
  background-repeat: no-repeat;
  background-size: 100% 4px, 4px 100%;
}
.credit__main .credit__container .credit__content .credit__col {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  margin: 15px 0;
}
.credit__main .credit__container .credit__content .credit__col .credit__row {
  width: 141px;
  height: 119px;
  background: #f6f6f6;
  border-radius: 2px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  padding: 12px 8px 18px;
  margin: 2px;
}
.credit__main .credit__container .credit__content .credit__col .credit__row img {
  width: 55px;
  height: 55px;
}
.credit__main .credit__container .credit__content .credit__col .credit__row h3 {
  font-weight: 700;
  font-size: 10px;
  line-height: 15px;
  text-align: center;
}
.credit__main .credit__container .credit__content .credit__text {
  font-size: 9px;
  line-height: 11px;
  color: var(--main-color);
  margin-bottom: 20px;
}
</style>