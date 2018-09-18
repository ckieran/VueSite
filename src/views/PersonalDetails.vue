<template>
<div class="personalDetails">
  <h1>Personal Details</h1>
  <div>
    <TextBox elementName="firstName" displayName="First Name" />
    <TextBox elementName="lastName" displayName="Last Name" />
  </div>
</div>
</template>

<script>
import TextBox from '@/components/TextBox.vue'

export default {
  name: 'personalDetails',
  components: {
    TextBox
  }
}
</script>
