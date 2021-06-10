<template>
  <div>Vue CLI</div>
</template>

<script>
import { defineComponent, onMounted } from "vue";
import { connect } from "twilio-video";

export default defineComponent({
  setup() {
    onMounted(() => {
      console.log(connect)
    })
  }
})
</script>
