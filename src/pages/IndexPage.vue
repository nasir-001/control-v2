<template>
  <div>
    <introduction></introduction>
    <hero></hero>
    <note></note>
    <mission></mission>
    <bot></bot>
    <team></team>
    <scholars></scholars>
  </div>
</template>

<script>
import { defineComponent } from "vue";
import Introduction from "components/Introduction.vue";
import Hero from "components/Hero.vue";
import Note from "components/Note.vue";
import Mission from "components/Mission.vue";
import Bot from "components/Bot.vue";
import Team from "components/Team.vue";
import Scholars from "components/Scholars.vue";

export default defineComponent({
  components: { Introduction, Hero, Note, Mission, Bot, Team, Scholars },
  name: "IndexPage",
});
</script>
