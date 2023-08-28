<template>
  <div>
    <Form/>
    
  </div>
</template>

<script>
import Form from "./modules/formulario/components/Form.vue";

export default {
  data() {
    return {
      showConfirmation: false
    };
  },
  methods: {
    
  },
  components: {
    Form,

  }
};
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;

  -webkit-font-smoothing: antialiased;

  -moz-osx-font-smoothing: grayscale;

  text-align: center;

  color: #2c3e50;

  

  margin: 60px;
}
</style>