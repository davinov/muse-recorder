<template>
  <div id="muse-recorder-app">
    <MuseRecorder/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import MuseRecorder from './components/MuseRecorder.vue';

@Component({
  components: {
    MuseRecorder,
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
#muse-recorder-app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
  height: 100%;
  overflow: hidden;
}
</style>
