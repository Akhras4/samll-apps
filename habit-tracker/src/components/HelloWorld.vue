<template>
  <div class="hello">
    <h1>{{ message }}</h1>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  data() {
    return {
      message: "Hello, TypeScript!"
    };
  }
});
</script>

<style lang="scss">
.hello {
  h1 {
    color: #42b983;
  }
}
</style>
