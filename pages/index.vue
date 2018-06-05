<template>
  <section class="section">
    <span :for="menu in menus" :key="menu">
      <nuxt-link :to="'/menu/' + menu" class="button is-success is-rounded">
          {{menu}}
        </nuxt-link>
    </span>
  </section>
</template>

<script>
  import myMenus from '~/assets/menu.json';

  let objMenus = JSON.parse(myMenus);
  

  export default {
    data() {
      return {menus: objMenus.data.message};
    },
    asyncData() {
      return {};
      }
  }
</script>