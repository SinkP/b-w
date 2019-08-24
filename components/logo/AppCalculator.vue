<template>
  <div class = "calculator">
        <div class="container">
            <div class="calculator__inner">
                    <h2 class="calculator__title">Калькулятор цен</h2>
                    <form action>
                        <div class="calculator__logotip">
                            <h3>Количество логотипов</h3>
                            <input type="text" placeholder="0" maxLength = "7" />
                        </div>
                        <div class="calculator__haveLogo">
                            <h3>Есть готовый логотип</h3>
                            <div class="calculator__radio">
                                <div class="calculator__radio-yes">
                                    <input
                                    class="calculator__radio-input"
                                    name="radioVariants"
                                    type="radio"
                                    id="check1"
                                    />
                                    <label class="calculator__radio-label" for="check1">Да</label>
                                </div>
                                <div class="calculator__radio-no">
                                    <input
                                    class="calculator__radio-input"
                                    name="radioVariants"
                                    type="radio"
                                    id="check2"
                                    />
                                    <label class="calculator__radio-label" for="check2">Нет</label>
                                </div>
                            </div>
                        </div>
                        <div class="calculator__type">
                            <h3>Тип логотипа</h3>
                            <input type="text" placeholder="Тип">
                        </div>
                        <div class="calculator__total">
                            <h3>Итого</h3>
                            <div class="calculator__price">1613 ₽</div>
                            <input type="submit" value = "Уже хочу логотип">
                        </div>
                    </form>
            </div>
        </div>
  </div>
</template>


<style scoped lang='sass'>

    .calculator
        background-color: #000
        padding-top: 30px
        padding-bottom: 30px

    .calculator__title
        color: #ffffff
        font-family: Roboto
        font-size: 30px
        font-weight: 100
        line-height: 22px
        text-align: center
         

    .calculator__logotip
        margin-top: 25px
        text-align: center
        h3
            color: #ffffff
            font-family: Roboto
            font-size: 20px
            font-weight: 100
            line-height: 22px
            margin-bottom: 17px
        input
            text-align: center
            width: 194px
            height: 41px
            background-color: #000 
            border: 1px solid #ffffff
            color: #ffffff
            font-family: Roboto

    .calculator__haveLogo
        margin-top: 25px
        text-align: center
        h3
            color: #ffffff
            font-family: Roboto
            font-size: 20px
            font-weight: 100
            line-height: 22px
            margin-bottom: 17px
        .calculator__radio
            display: flex
            justify-content: center
            color: #ffffff
            font-family: Roboto
            font-size: 16px
            font-weight: 100
            line-height: 22px

        .calculator__radio-yes
            margin-right: 50px

        .calculator__radio-input
            appearance: none
            position: absolute

        .calculator__radio-label
            position: relative
            cursor: pointer
            padding-left: 30px
            &:before
                content: ""
                display: block
                width: 23px
                height: 23px
                background-color: #000000
                border: 1px solid #ffffff
                position: absolute
                left: 0
                top: 0
            &:after
                content: ""
                display: block
                width: 16px
                height: 16px
                left: 3px
                top: 4px
                background-color: green
                opacity: 0
                position: absolute

    .calculator__radio-input:checked + .calculator__radio-label:after
        opacity: 1
    
    .calculator__type
        margin-top: 25px
        text-align: center
        border-bottom: 1px dashed #ffffff
        padding-bottom: 40px
        h3
            color: #ffffff
            font-family: Roboto
            font-size: 20px
            font-weight: 100
            line-height: 22px
            margin-bottom: 17px
        input
            text-align: center
            width: 194px
            height: 41px
            background-color: #000 
            border: 1px solid #ffffff
            color: #ffffff
            font-family: Roboto
            padding-left: 10px
            padding-right: 10px

    .calculator__total
        text-align: center
        margin-top: 24px
        h3
            color: #ffffff
            font-family: Roboto
            font-size: 20px
            font-weight: 100
            line-height: 22px
            margin-bottom: 5px
        .calculator__price
            color: #ffffff
            font-family: Roboto
            font-size: 30px
            font-weight: 100
            line-height: 30px
            margin-bottom: 17px
        input
            color: #ffffff
            font-family: Roboto
            font-size: 20px
            font-weight: 100
            line-height: 24px
            border: 1px solid #ffffff
            background-color: #000
            padding: 21px 50px
            cursor: pointer
            transition: background-color .2s linear, 
            border .2s linear
            &:hover
                background-color: #3b2828
                border-color: #624b4b
</style>
