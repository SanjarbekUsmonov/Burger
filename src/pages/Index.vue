<template >
  <div>
    <CompBuild/>
    <CompSyle/>
    <CompSeeOur/>
    <CompYourcan/>
    <CompPricing/>
  </div>
</template>
<script>
import CompBuild from 'src/components/CompBuild';
import CompSyle from 'src/components/CompSyle';
import CompSeeOur from '../components/CompSeeOur';
import CompYourcan from 'src/components/CompYourcan';
import CompPricing from 'src/components/CompPricing';
export default {
    components: {
    CompBuild,
    CompSyle,
    CompSeeOur,
    CompYourcan,
    CompPricing
}
}
</script>
<style scoped>

</style>
