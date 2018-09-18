<template>
<div>
  <label v-bind:for="elementName">{{displayName}}</label>
  <input v-bind:id="elementName" type="text" />
</div>
</template>
<script>
export default {
  name: 'TextBox',
  props: {
    elementName: String,
    displayName: String
  }
}
</script>
<style scoped>
 div {
   margin-bottom:10px;
 }
 input {
   margin-left:10px;
  }
</style>
