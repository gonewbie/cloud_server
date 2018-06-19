<template>
  <section class="section">
<<<<<<< HEAD
    <span v-for="menu in menus" :key="menu">
=======
    <span :for="menu in menus" :key="menu">
>>>>>>> cf3150ed2960e0d252c4b8db730da794515c6bd7
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