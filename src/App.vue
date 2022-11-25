<template>
  <div>
    <HeadePage/>
    <MainPage/>
    <FooterPage/>
  </div>
</template>

<script>

import HeadePage from '@/components/HeadePage.vue';

import MainPage from '@/components/MainPage.vue';
import FooterPage from '@/components/FooterPage.vue';

export default {
  components: {
    HeadePage,
    MainPage,
    FooterPage,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
