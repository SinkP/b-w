<template>
  <section class="black">
    <app-header></app-header>

    <div class="spickDo">
      <div class="container">
        <h2 class="spickDo__title">
          Меньше слов<br />
          Больше дела
        </h2>
      </div>
    </div>

    <div class="content">
      <div class="container">
        <div class="content__inner">
          <div class="content__title">Сайт</div>
          <div class="content__subtitle">Создание сайта любой сложности</div>
          <div class="content__btn">
            <a href="#">Подробнее</a>
          </div>
        </div>
      </div>
    </div>

    <div class="content">
      <div class="container">
        <div class="content__inner">
          <div class="content__title">Дизайн</div>
          <div class="content__subtitle">Создание сайта любой сложности</div>
          <div class="content__btn">
            <a href="#">Подробнее</a>
          </div>
        </div>
      </div>
    </div>

    <div class="content">
      <div class="container">
        <div class="content__inner">
          <div class="content__title">Логотип</div>
          <div class="content__subtitle">Создание сайта любой сложности</div>
          <div class="content__btn">
            <a href="#">Подробнее</a>
          </div>
        </div>
      </div>
    </div>

    <footer class = "footer">
      <div class="container">
        <div class="footer__inner">
          <div class="footer__title">
            Немного о нас
          </div>
          <div class="footer__subtitle">
            Собралась как-то команда<br>
            профессионалов<br>
            перфекционистов, <br>
            уставшая от дерьмовых<br>
            исполнителей заказов и<br>
            основала эту студию<br>
            Конец :D
          </div>
        </div>
      </div>
    </footer>
  </section>
</template>

<script>
import appHeader from "../components/themain/AppHeader.vue";

export default {
  components: {
    appHeader
  }
};
</script>

<style scoped lang="sass" >

  .spickDo
    background-color: #000
    padding-top: 25px
    border-bottom: 1px solid  #646464

  .spickDo__title
    color: #ffffff
    font-family: Roboto
    font-size: 30px
    font-weight: 100
    line-height: 30px
    text-align: center
    padding-bottom: 20px

  .content
    text-align: center
   
    padding-top: 20px
    padding-bottom: 20px
    background-color: #000
    border-bottom: 1px solid  #646464

  .content__title
    color: #ffffff
    font-family: Roboto
    font-size: 20px
    font-weight: 100
    line-height: 24px
    margin-bottom: 15px

  .content__subtitle
    color: #ffffff
    font-family: Roboto
    font-size: 16px
    font-weight: 100
    line-height: 24px

  .content__btn
    a
      display: inline-block
      color: #ffffff
      font-family: Roboto
      font-size: 16px
      font-weight: 100
      line-height: 24px
      padding: 8px 70px
      border: 1px solid #fff
      margin-top: 10px
      transition: background-color .2s linear, 
      border .2s linear
      &:hover
           background-color: #3b2828
           border-color: #624b4b

  .footer
    background-color: #000
    text-align: center    
    padding-top: 25px
    padding-bottom: 45px


  .footer__title
    color: #ffffff
    font-family: Roboto
    font-size: 30px
    font-weight: 100
    line-height: 30px
    margin-bottom: 28px

  .footer__subtitle
    margin-top: 
    color: #ffffff
    font-family: Roboto
    font-size: 20px
    font-weight: 100
    line-height: 22px
</style>

