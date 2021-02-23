<template>
<div>
    <div class="art-mobile-top-bar"></div>
    <div class="art-app-wrapper">
      <div class="art-app-container">
       
       <Infobar></Infobar> 
       <Menubar></Menubar>
       <Content></Content>
     
      </div>

    </div>
    <Preloader></Preloader>
</div>
</template>

<script>
import Infobar from './components/Infobar.vue';
import Content from './components/Content.vue';
import Menubar from './components/Menubar.vue';
import Preloader from './components/Preloader.vue';

export default {
  components:{
    Infobar,
    Content,
    Menubar,
    Preloader
  }
 
};
</script>
