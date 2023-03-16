<template>
  <div>
    <introduction></introduction>
    <hero></hero>
    <note></note>
    <mission></mission>
    <bot></bot>
  </div>
</template>

<script>
import { defineComponent } from "vue";
import Introduction from "components/Introduction.vue";
import Hero from "components/Hero.vue";
import Note from "components/Note.vue";
import Mission from "components/Mission.vue";
import Bot from "components/Bot.vue";

export default defineComponent({
  components: { Introduction, Hero, Note, Mission, Bot },
  name: "IndexPage",
});
</script>
