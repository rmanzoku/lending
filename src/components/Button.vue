<template>
  <button class="m-button" @click="click">
    <slot />
  </button>
</template>

<script>
export default {
  methods: {
    click() {
      this.$emit('click');
    },
  },
};
</script>

<style>
.m-button {
  padding: 0.5em 1em;
  font-size: 17px;
  background: #668ad8;
  color: #ffffff;
  border-radius: 4px;
}
.m-button:hover {
  background: #668aee;
  color: #ffffff;
}
</style>