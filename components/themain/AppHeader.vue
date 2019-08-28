<template>
  <header class="header">
    <div class="container">
      <div class="header__inner">
        <h1 class="header__title">
          Всё, что <br>
          тебе нужно <br>
          В одном <br>
          месте <br>
        </h1>
        <h2 class="header__subtitle">
          Прогрессивная веб-студия
        </h2>
        <div class="header__logo">
          <a href="#">B&amp;W</a>   
        </div>
        <div class="header__arrow">
          <img src="../../static/Logotyps/header__arrow.svg" alt="arrow" />
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped lang='sass'>

  .header
    padding-top: 36px
    padding-bottom: 25px
    background-image: url("../../static/themain/bg_header.png")
    width: 100%
    background-repeat: no-repeat
    background-size: cover
    position: relative
    z-index: 0
    &:after
        content: ''
        display: block
        position: absolute
        left: 0
        top: 0
        right: 0
        bottom: 0
        background-color: rgba(#000, 0.57)
        z-index: -1
      


  .header__title
    color: #ffffff
    font-size: 48px
    font-weight: 100
    line-height: 48px
    font-family: Roboto
    margin-bottom: 14px

  .header__subtitle
    color: #ffffff
    font-family: Roboto
    font-size: 20px
    font-weight: 100
    line-height: 24px
    margin-bottom: 10px
    opacity: 0.7
  
  .header__logo
    text-align: center
    margin-bottom: 35px;
    a
      text-transform: uppercase
      font-size: 20px
      color: #171717
      padding: 10px 15px
      background-color: #ffffff
      font-family: Roboto
      font-weight: 100
  
  .header__arrow
    text-align: center
    
</style>