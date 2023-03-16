<template>
  <div>
    <introduction></introduction>
    <hero></hero>
    <note></note>
  </div>
</template>

<script>
import { defineComponent } from "vue";
import Introduction from "components/Introduction.vue";
import Hero from "components/Hero.vue";
import Note from "components/Note.vue";

export default defineComponent({
  components: { Introduction, Hero, Note },
  name: "IndexPage",
});
</script>
