<template>
  <div id="app">
    <AppHeader />
    <HomeComponent />
    <IndexProjectComponent />
    <AchievmentsComponent />
    <IndexBlogComponent />
    <AppFooter />
  </div>
</template>

<script>

import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import HomeComponent from './components/HomeComponent.vue';
import AchievmentsComponent from './components/AchievmentsComponent.vue';
import IndexBlogComponent from './components/IndexBlogComponent.vue';
import IndexProjectComponent from './components/IndexProjectComponent.vue';


export default {
  name: 'App',
  components: {
    AppHeader,
    HomeComponent,
    IndexBlogComponent,
    IndexProjectComponent,
    AchievmentsComponent,
    AppFooter
  }
}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    text-decoration: none;
}
body{
    background-color: #ffff;
    font-family: "DM Serif Display", serif;
}
ul, li{
    list-style-type: none;
}

.box-content{
    overflow: hidden;
}


.container {
    padding-left: calc(50% - 1200px / 2);
    padding-right: calc(50% - 1200px / 2);
}
</style>
