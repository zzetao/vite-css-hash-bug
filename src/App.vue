<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
  <hr/>
  <Component01 />
  <Component02 />
  <Component03 />
  <Component04 />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Component01 from './components/Component01.vue'
import Component02 from './components/Component02.vue'
import Component03 from './components/Component03.vue'
import Component04 from './components/Component04.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Component01,
    Component02,
    Component03,
    Component04,
  }
}
</script>
