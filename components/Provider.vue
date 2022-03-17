<template>
  <div style="border: 2px solid blue">
    <h2>provider</h2>
    <slot></slot>
  </div>
</template>

<script>
export default {
  provide() {
    return {
      providedValue: 'FOO',
    }
  },
}
</script>
