<template>
  <section class="section">
    <div class="columns is-centered">
      <span v-for="menu in menus" :key="menu">
      <nuxt-link :to="'/menu/' + menu" class="box">
        <!--<figure class="image">
          <img :src="'~assets/' + menu +'.png'" alt="">
        </figure>-->
        {{menu}}
        </nuxt-link>
      </span>
    </div>
  <!--<div>Icons made by <a href="https://www.flaticon.com/authors/smashicons" title="Smashicons">Smashicons</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>-->
  </section>
</template>

<script>
  let objMenus = ["introduce", "footstep", "self-improvement"];
  
  export default {
    data() {
      return {menus: objMenus};
    },
    asyncData() {
      return {};
      }
  }
</script>