<template>
  <div class="choose__card">
    <a href="/about">
      <div class="card__img">
        <picture>
          <img src="../assets/mustang.png" alt="mustang" />
        </picture>
      </div>
    </a>
    <div class="card__main">
      <a href="">
        <span class="card__name">HAVAL H9</span>
      </a>
      <p class="card__set">COMFORT 2.0D 8АТ (190 л.с.)</p>
      <div class="card__price">
        <span>от 2 669 000 ₽</span>
        <del>от 3 999 000 ₽</del>
      </div>
      <div class="card__bottom">
        <p>от 50 245 ₽/мес.</p>
        <button class="card__btn modal__credit-btn">В кредит</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.choose__card {
  width: 280px;
  height: auto;
}
.card__img {
  width: 280px;
  max-height: 210px;
  height: 100vh;
  border-radius: 10px 10px 0 0;
  background: #2a4daf26;
}
.card__img img {
  width: 280px;
  height: auto;
  border-radius: 10px 10px 0 0;
}
.card__main {
  background: var(--white-color);
  -webkit-box-shadow: var(--box-shadow);
  box-shadow: var(--box-shadow);
  padding: 10px;
}
.card__name {
  font-weight: 700;
  font-size: 18px;
  text-transform: capitalize;
}
.card__set {
  font-weight: 600;
  font-size: 12px;
  color: var(--blue-color);
  margin-top: 5px;
}
.card__price {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  margin: 20px 0;
}
.card__price span {
  font-weight: 700;
  font-size: 18px;
  color: var(--secondary-color);
}
.card__price p {
  font-size: 12px;
  -webkit-text-decoration-line: line-through;
  text-decoration-line: line-through;
  color: var(--secondary-color);
}
.card__bottom {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  border-top: 1px solid #e3e3e5;
  padding-top: 15px;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}
.card__bottom p {
  font-weight: 500;
  font-size: 10px;
  line-height: 24px;
  color: var(--red-color);
}
.card__btn {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  width: 134px;
  height: 34px;
  font-weight: 700;
  font-size: 12px;
  line-height: 24px;
  color: var(--white-color);
  background: var(--blue-color);
  border-radius: 5px;
  -webkit-transition: all 0.4s ease;
  -o-transition: all 0.4s ease;
  transition: all 0.4s ease;
}
.card__btn:hover {
  color: var(--blue-color);
  background: var(--white-color);
  border: 1px solid var(--blue-color);
}
.choose__btn {
  margin-top: 215px;
  width: 267px;
  height: 35px;
  font-weight: 700;
  font-size: 12px;
  line-height: 24px;
  color: var(--blue-color);
  background: var(--white-color);
  border-radius: 5px;
  padding: 5px 88px;
  -webkit-transition: all 0.4s ease;
  -o-transition: all 0.4s ease;
  transition: all 0.4s ease;
  margin-bottom: 40px;
}
.choose__btn:hover {
  color: var(--white-color);
  background: var(--blue-color);
}

.show__btn.d-none {
  display: none;
}
</style>