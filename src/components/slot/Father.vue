<template>
  <div>
    <son>
      <p slot="header">...header...</p>
      <p slot="footer">...header...</p>
    </son>
  </div>
</template>

<script>
import Son from '@/components/slot/Son'
export default {
  components: {
    Son
  }
}
</script>

<style lang='scss' scoped>
</style>
