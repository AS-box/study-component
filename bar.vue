<template>
  <div class="bar">
    <h1 class="header">Barコンポーネント</h1>
    <p>これはBarコンポーネントです。</p>
    <foo />
  </div>
</template>
<script>
import Foo from './foo'
export default {
  components:{
    Foo
  }
}
</script>
<style scoped>
.bar{
  border:solid 1px red;
  margin:4px;
  padding: 4px;
}
.header{
  color: red;
}
</style>
