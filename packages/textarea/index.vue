<template>
  <div class="eui-textarea-hello">
    <h1>{{ msg }}</h1>
    <div>这是textarea组件</div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "TextArea",
  props: {
    msg: String
  }
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.eui-textarea-hello {
  color: red;
}
</style>
