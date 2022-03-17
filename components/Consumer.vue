<template>
  <div style="border: 2px solid green">
    <h3>consumer</h3>
    provided value: {{ formattedProvidedValue }}
  </div>
</template>

<script>
export default {
  inject: ['providedValue'],
  computed: {
    formattedProvidedValue() {
      return this.providedValue.toLowerCase()
    },
  },
}
</script>
