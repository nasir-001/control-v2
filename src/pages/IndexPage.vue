<template>
  <div>
    <introduction></introduction>
  </div>
</template>

<script>
import { defineComponent } from "vue";
import Introduction from "components/Introduction.vue";

export default defineComponent({
  components: { Introduction },
  name: "IndexPage",
});
</script>
