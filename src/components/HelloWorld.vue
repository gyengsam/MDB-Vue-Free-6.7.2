<template>
  <div class="container">
    <div>First Page</div>
    <mdb-btn outline="primary">Primary</mdb-btn>
    <mdb-btn color="pink">Pink</mdb-btn>
    <mdb-btn gradient="peach" rounded>Peach gradient button</mdb-btn>
    
    <div>
      <mdb-btn tag="a" gradient="purple" floating size="lg"><mdb-icon icon="bolt"/></mdb-btn>
      <mdb-btn tag="a" gradient="peach" floating><mdb-icon icon="leaf"/></mdb-btn>
      <mdb-btn tag="a" gradient="blue" floating size="sm"><mdb-icon icon="star"/></mdb-btn>
    </div>
    <div>
      <mdb-btn outline="primary" darkWaves rounded>Primary outline button</mdb-btn>
    </div>
  </div>
  
</template>

<script>
import { mdbBtn, mdbIcon } from 'mdbvue';

export default {
  name: 'ButtonPage',
  components: {
    mdbBtn,
    mdbIcon
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
