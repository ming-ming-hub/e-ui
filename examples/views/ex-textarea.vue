<template>
  <div class="home">
    <Textarea msg="调用时候传入textaarea的msg" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Textarea } from "../../packages";
export default defineComponent({
  name: "ex-textarea",
  components: {
    Textarea
  }
});
</script>
