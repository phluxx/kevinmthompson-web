<template>
  <div class="home">
    <ComingSoon />
  </div>
</template>

<script>
import ComingSoon from '../components/ComingSoon.vue';

export default {
  components: {
    ComingSoon,
  },
};
</script>

<style>
.home {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
</style>

