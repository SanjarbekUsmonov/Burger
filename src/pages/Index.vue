<template >
  <div>
    <CompBuild/>
    <CompSyle/>
    <CompSeeOur/>
  </div>
</template>
<script>
import CompBuild from 'src/components/CompBuild';
import CompSyle from 'src/components/CompSyle';
import CompSeeOur from '../components/CompSeeOur';
export default {
    components: {
     CompBuild,
     CompSyle,
     CompSeeOur
  }
}
</script>
<style scoped>

</style>
