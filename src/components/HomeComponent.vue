<template>
          <div class="home container">
        <img src="Img/Images.svg" alt="" class="home_img">
        <div class="home_content">
          <p class="home_heading">Пусть ваш дом будет уникальным</p>
          <p class="home_info">
            Существует много вариаций Lorem Ipsum, которые можно использовать
          </p>
          <button class="home_btn">
            Начать
            <img src="Img/Vector.png" alt="" class="home_arrow" />
          </button>
        </div>
      </div>
</template>

<script>
export default {
  name: "HomeComponent",
};
</script>

<style>
.home{
    margin-top: 74px;
    height: 758px;
}
    .home_img{
        position: relative;
        display:flex;
    }
    .home_content{
        position: absolute;
        top: 44%;
        left:21%;
    }
    .home_heading{
        color: #292F36;
        font-size: 65px;
        width: 525px;
        margin-bottom: 18px;
    }
    .home_info{
        color: #4D5053;
        font-size: 22px;
        width: 433px;
        margin-bottom: 21px;
    }
    .home_btn{
        color: #FFFFFF;
        font-size: 18px;
        border: none;
        border-radius: 18px;
        background-color: #292F36;
        width: 183px;
        height: 75px;
        display: flex;
        gap: 4.91px;
        align-items: center;
        justify-content: center;
    }
</style>