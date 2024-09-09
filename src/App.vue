


<script>
import TemplateComponent from './components/TemplateComponent.vue';
// my-component.js
export default {
  data() {
    return { 
      count: 0 
    }
  },
  components:{
    TemplateComponent
  }
}
</script>

<template>
  <TemplateComponent />
  <h1>{{ count }}</h1>
</template>

<style scoped>

</style>
