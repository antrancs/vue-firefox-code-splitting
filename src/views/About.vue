<template>
  <div class="about"><h1>This is an about page</h1></div>
</template>

<script lang="ts">
import lodash from "lodash";
import { Component, Vue } from "vue-property-decorator";

@Component
export default class About extends Vue {
  created() {
    console.log(lodash);
  }
}
</script>
