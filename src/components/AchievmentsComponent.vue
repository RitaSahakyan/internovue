<template>
          <div class="achievments">
        <div class="achievments_box">
          <p class="achievments_number">12</p>
          <p class="achievments_descr">Лет опыта</p>
        </div>
        <div class="achievments_line"></div>
        <div class="achievments_box">
          <p class="achievments_number">85</p>
          <p class="achievments_descr">Успешных проектов</p>
        </div>
        <div class="achievments_line"></div>
        <div class="achievments_box">
          <p class="achievments_number">15</p>
          <p class="achievments_descr">Проектов в работе</p>
        </div>
        <div class="achievments_line"></div>
        <div class="achievments_box">
          <p class="achievments_number">95</p>
          <p class="achievments_descr">Счастливых клиентов</p>
        </div>
      </div>
</template>

<script>
export default {
  name: "AchievmentsComponent",
};
</script>

<style>
.achievments{
    display: flex;
    justify-content: center;
    align-self: center;
    height: 457px;
    background-color: #F4F0EC;
    margin-top: 96px;
}
.achievments_number{
        color:#CDA274;
        font-size: 85px;
    }
.achievments_descr{
        color: #4D5053;
        font-size: 22px;
    }
.achievments_box{
        margin-top: 151px;
        width: 207px;
        text-align: center;
        margin-right: 33px;
    }
.achievments_line{
        margin-top: 151px;
        width: 1px;
        height: 130px;
        background-color: #CDA274;
        margin-right: 33px;
    }
</style>