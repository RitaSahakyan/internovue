<template>
          <div class="proj_section-heading container">
        <p class="proj_section_heading">Следите за нашими проектами</p>
        <p class="proj_section_info">
          Хорошо известно, что читатель будет отвлекаться на читабельный контент
          страницы
        </p>
      </div>
      <div class="project container">
        <div class="project_items">
          <img src="Img/Proj1.svg" alt="" class="project_img" />
          <div class="project_item_container">
            <div class="project_item-content">
              <h4 class="project_item-name">Совеменная кухня</h4>
              <p class="project_item-info">Декор / Планировка</p>
            </div>
            <button class="project_item-button">
              <img src="Img/arrow.png" alt="" class="project_btn-arrow" />
            </button>
          </div>
        </div>
        <div class="project_items">
          <img src="Img/Proj2.svg" alt="" class="project_img" />
          <div class="project_item_container">
            <div class="project_item-content">
              <h4 class="project_item-name">Совеменная кухня</h4>
              <p class="project_item-info">Декор / Планировка</p>
            </div>
            <button class="project_item-button">
              <img src="Img/arrow.png" alt="" class="project_btn-arrow" />
            </button>
          </div>
        </div>
        <div class="project_items">
          <img src="Img/Proj3.svg" alt="" class="project_img" />
          <div class="project_item_container">
            <div class="project_item-content">
              <h4 class="project_item-name">Совеменная кухня</h4>
              <p class="project_item-info">Декор / Планировка</p>
            </div>
            <button class="project_item-button">
              <img src="Img/arrow.png" alt="" class="project_btn-arrow" />
            </button>
          </div>
        </div>
        <div class="project_items">
          <img src="Img/Proj4.svg" alt="" class="project_img" />
          <div class="project_item_container">
            <div class="project_item-content">
              <h4 class="project_item-name">Совеменная кухня</h4>
              <p class="project_item-info">Декор / Планировка</p>
            </div>
            <button class="project_item-button">
              <img src="Img/arrow.png" alt="" class="project_btn-arrow" />
            </button>
          </div>
        </div>
      </div>
</template>

<script>
export default {
  name: "IndexProjectComponent",
};
</script>

<style>
.proj_section-heading{
display: flex;
flex-direction: column;
text-align: center;
margin-top: 91px;
margin-bottom: 93px;
}
.proj_section_heading{
    font-size: 50px;
    color: #292F36;
    text-align: center;
}
.proj_section_info{
    font-size: 22px;
    color: #4D5053;
    text-align: center;
    width: 490px;
    margin-left: 392px;
    line-height: 150%;
    margin-top: 8px;
}

.project{
    display: flex;
    flex-wrap: wrap;
    gap: 56px;
}
    .project_items{
        width: 548px;
        height: 619px;
    }
    .project_item_container{
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        margin-top: 28px;
    }    
    .project_img{
        height: 525px;
        width: 548px;
    }
    .project_item-info{
        color: #4D5053;
        font-size: 22px;
        line-height: 150%;
    }
    .project_item-name{
        color:#292F36;
        font-size: 28px;
        line-height: 125%;
    }
    .project_item-button{
        background-color: #F4F0EC;
        border:none;
        width: 70px;
        height: 70px;
        border-radius: 100px;
    }
    .project__btn-arrow{
        height: 18px;
        width: 8px;
    }
</style>