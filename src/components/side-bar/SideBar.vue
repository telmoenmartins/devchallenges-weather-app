<template>
  <div class="sidebar">
    <div class="text">side bar text</div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class Sidebar extends Vue {}
</script>

<style lang="scss" scoped>
$sidebar-color: #1e213a;

.sidebar {
  width: 30%;
  height: 100%;
  background-color: $sidebar-color;
}
</style>
