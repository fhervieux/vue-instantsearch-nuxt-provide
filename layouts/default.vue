<template>
  <div style="border: 2px solid red">
    <h1>default layout</h1>
    <Provider>
      <Nuxt />
    </Provider>
  </div>
</template>

<script>
import Provider from '~/components/Provider.vue'

export default {
  components: {
    Provider,
  },
}
</script>
