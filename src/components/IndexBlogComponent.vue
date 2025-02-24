<template>
          <div class="blog container">
            <div class="blog_content">
          <p class="blog_heading">Статьи & Новости</p>
          <p class="blog_info">
            Хорошо известно, что читатель будет отвлекаться на читабельный
            контент страницы
          </p>
        </div>
        <div class="blog_articles">
          <div class="blog_articles-item">
            <img src="Img/News1.svg" alt="" class="blog_articles-img" />
            <div class="blog_articles-img-Text">Дизайн кухни</div>
            <div class="blog_articles-heading">
              Создадим лучший макет перепланировки
            </div>
            <div class="blog_articles-footer">
              <div class="blog_articles-text">26 Декабрь,2022</div>
              <button class="blog_articles-btn">
                <img src="Img/arrow.png" alt="" class="blog_articles-arrow" />
              </button>
            </div>
          </div>
          <div class="blog_articles-item">
            <img src="Img/News2.svg" alt="" class="blog_articles-img" />
            <div class="blog_articles-img-Text">Дизайн для жизни</div>
            <div class="blog_articles-heading">
              Лучшие интерьерные идеи по низкой цене
            </div>
            <div class="blog_articles-footer">
              <div class="blog_articles-text">22 Декабрь,2022</div>
              <button class="blog_articles-btn-2">
                <img src="Img/arrow.png" alt="" class="blog_articles-arrow" />
              </button>
            </div>
          </div>
          <div class="blog_articles-item">
            <img src="Img/News3.svg" alt="" class="blog_articles-img" />
            <div class="blog_articles-img-Text">Дизайн Интерьера</div>
            <div class="blog_articles-heading">
              Лучшие интерьерные решения для офисов
            </div>
            <div class="blog_articles-footer">
              <div class="blog_articles-text">25 Декабрь,2022</div>
              <button class="blog_articles-btn">
                <img src="Img/arrow.png" alt="" class="blog_articles-arrow" />
              </button>
            </div>
          </div>
        </div>
      </div>
</template>

<script>
export default {
  name: "IndexBlogComponent",
};
</script>

<style>
    .blog_content{
        margin-top: 96px;
        margin-bottom: 52px;
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
    }
    .blog_heading{
        font-size: 50px;
        color: #292F36;
        width: 362px;
    }
    .blog_info{
        margin-top: 12px;
        width: 481px;
        font-size: 22px;
        color: #4D5053;
    }
    .blog_articles{
        height: 521px;
        display: flex;
        gap: 27px;
    }   
    .blog_articles-item{
        border: 1px solid #E7E7E7;
        background-color: #F4F0EC;
        border-radius: 15%;
        width: 382px;
    }
    .blog_articles-item:first-child{
            background-color: #FFFFFF;
            border: 1px solid #E7E7E7;
            border-radius: 15%;
            width: 382px;
    }
    .blog_articles-item:last-child{
            background-color: #FFFFFF;
            border: 1px solid #E7E7E7;
            border-radius: 15%;
            width: 382px;
    }
    .blog_articles-img {
        padding: 21px 21px 21px 21px;
        display: flex;
        position: relative;
    }
    .blog_articles-img-Text{
        position: absolute;
        background-color: #FFFFFF;
        font-size: 16px;
        width: 129px;
        height: 40px;
        color: #4D5053;
        display: flex;
        align-items: center;
        justify-content: center;
        margin-left: 40px;
        margin-top: -90px;
        border-radius: 10px 10px 10px 0;
    }
    .blog_articles-heading{
        font-size: 25px;
        color: #292F36;
        margin: 0 21px;
    }
    .blog_articles-footer{
        margin: 30px 21px 21px 21px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .blog_articles-text{
            font-size: 16px;
            color: #4D5053;
        }
        .blog_articles-btn{
            background-color: #F4F0EC;
        border:none;
        width: 52px;
        height: 52px;
        border-radius: 100px;
        }
        .blog_articles-btn-2{
            width: 52px;
            height: 52px;
            background-color: #FFFFFF;
            border-radius: 50%;
            border: none;
        }
</style>