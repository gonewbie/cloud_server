<template>
  <section class="section">
    <span v-for="menu in menus" :key="menu">
      <nuxt-link :to="'/menu/' + menu" class="button is-success is-rounded">
          {{menu}}
        </nuxt-link>
    </span>
  </section>
</template>

<script>
  let objMenus = ["Introduce", "Footstep", "Self-Improvement"];
  //let objMenus = JSON.parse(myMenus);
  

  export default {
    data() {
      //return {menus: objMenus.data.message};
      return {menus: objMenus};
    },
    asyncData() {
      return {};
      }
  }
</script>