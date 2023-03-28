<template>
  <div class="header__topa">
    <div class="container">
      <ul class="header__top">
        <li>Каталог</li>
        <li>О компании</li>
        <li>Оплата и доставка</li>
        <li>гарантии и возвратt</li>
        <li>Сотрудничество</li>
        <li>Услуги</li>
        <li>Решения</li>
        <li>Техподдержка</li>
        <li>Контакты</li>
      </ul>
    </div>
  </div>
  <div class="container">
    <header-com/>
  </div>
</template>

<script>
import HeaderCom from './components/HeaderCom.vue';
export default {
  components:{
    HeaderCom
  }
}
</script>
<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container{
  max-width: 1420px;
  margin: 0 auto;
  padding: 0 102px;
  box-sizing: content-box;
}
@media(max-width: 1420px){
  .container{
    max-width: 1020px;
    margin: 0 auto;
    padding: 0 102px;
    box-sizing: content-box;
  }
  .header__bottom{
    display: none;
  }
}
</style>