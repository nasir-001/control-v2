<template>
  <div class="tw-mt-16">
    <div class="tw-text-center tw-text-5xl tw-leading-0 title gradien">
      <div class="tw-py-1">Introducing Chatislam</div>
    </div>
    <div
      class="tw-w-1/2 tw-text-center tw-mx-auto tw-text-base tw-tracking-wide tw-pt-3"
    >
      We are developing a conversational model called Chatislam, which will be
      train to interact with users on islam. Its dialogue-based format allows it
      to provide answers to follow-up questions, admit any mistakes it may make,
      challenge incorrect assumptions, and reject inappropriate requests.
    </div>
    <q-card-actions align="center">
      <q-btn
        color="primary"
        unelevated
        class="tw-w-36 tw-h-10 tw-rounded-3xl"
        no-caps
        label="Learn more"
      />
    </q-card-actions>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  setup() {},
});
</script>

<style scoped>
.title {
  background: linear-gradient(to right, #0b1e4f 0%, #fd8a45 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
