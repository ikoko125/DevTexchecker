<template>
  <main>
    <div id="box">
      <div v-for="i in 100" :key="i" class="box" />
    </div>
  </main>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style lang="scss" src=".\checker.scss" />