<template>
  <cv-header aria-label="Carbon header">
    <cv-header-name v-if="!portugues" href="javascript:void(0)">
      Leonardo Neves Resume 
    </cv-header-name>
    <cv-header-name v-else href="javascript:void(0)">
      Leonardo Neves CV 
    </cv-header-name>
    <span style="cursor: pointer;">
      <img v-if="!portugues"
        @click="language"
        style="border-radius: 3px; max-height: 10px;"
        src="../assets/brazilFlag.png"
        alt="portuguese selection" />
      <img v-if="portugues"
        @click="language"
        style="border-radius: 3px; max-height: 10px;"
        src="../assets/britishFlag.png"
        alt="english selection" />
    </span>
  </cv-header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      portugues: false
    }
  },
  methods: {
    language() {
      this.portugues = !this.portugues
      this.$emit('portuguese', this.portugues)
    }
  }
};
</script>
