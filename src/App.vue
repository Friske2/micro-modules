<template>
  <div>
    <HelloWorld></HelloWorld>
    <ModuleFirst msg="hello world"></ModuleFirst>
    <ModuleSecond></ModuleSecond>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from './components/HelloWorld.vue'
import ModuleFirst from './modules/ModuleFirst/ModuleFirst.vue'
import ModuleSecond from './modules/ModuleSecond/ModuleSecond.vue'
export default defineComponent({
  name: 'App',
  components: {
    HelloWorld,
    ModuleFirst,
    ModuleSecond
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
