<template>
  <div class="home">
    <side-bar></side-bar>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Sidebar from "@/components/side-bar/SideBar.vue";

@Component({
  components: { Sidebar },
})
export default class Home extends Vue {}
</script>

<style lang="scss" scoped>
.home {
  width: 100%;
}
</style>
