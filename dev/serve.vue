<script lang="ts">
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { SimplifyCssSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  SimplifyCssSample,
  // }
});
</script>

<template>
  <div id="app">
    <simplify-css-sample />
  </div>
</template>
