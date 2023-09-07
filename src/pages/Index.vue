<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    />
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',
  data() {
    return {
      obj: {
        t: 'ddd',
      },
    };
  },

  mounted() {
    console.log('djsf', this.obj?.t);
  },
};
</script>
