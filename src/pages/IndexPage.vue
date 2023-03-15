<template>
  <div>
    <introduction></introduction>
    <hero></hero>
  </div>
</template>

<script>
import { defineComponent } from "vue";
import Introduction from "components/Introduction.vue";
import Hero from "components/Hero.vue";

export default defineComponent({
  components: { Introduction, Hero },
  name: "IndexPage",
});
</script>
