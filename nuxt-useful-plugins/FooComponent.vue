<template>
  <div>
    <b>Name:</b> {{ user.name }}<br>
    <b>Email:</b> {{ user.email }}<br>
    <b>Registered On:</b> {{ formatDate(user.registered_on) }}
  </div>
</template>

<script>
export default {
    name: 'FoorComponent',
    props: {
      taxAuditor: {
        type: Object,
        required: true
      }
  }
}
</script>
