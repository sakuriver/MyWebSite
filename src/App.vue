<template>
    <div>Hello {{ value }}</div>
</template>

<script>
const VModal = window["vue-js-modal"].default
export default {
  name: "App",
  data() {
    return {
      value: "World"
    };
  }
};
Vue.use(VModal);
new Vue({
  el: '#app',
  methods: {
    show : function() {
      this.$modal.show('hello-world');
    },
    hide : function () {
      this.$modal.hide('hello-world');
    },
  }
});
</script>
