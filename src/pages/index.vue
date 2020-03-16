<template>
  <div class="container">
    <div>
      <h1 class="title">アセットレンディング</h1>
      <h2 class="subtitle">My exquisite Nuxt.js projectttt</h2>
      <Button @click="click">hogehoge</Button>
    </div>
  </div>
</template>

<script>
import Button from '~/components/Button.vue';

export default {
  components: {
    Button,
  },

  methods: {
    click() {
      console.log('app');
    },
  },
};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 90vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>

