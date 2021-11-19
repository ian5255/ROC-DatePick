<template lang="pug">
  ROCDatePick(v-model="ROCDate" :selectableYearRange="{from: 1, to: 150}")
</template>

<script>
import ROCDatePick from '@/views/ROCDatePick'

export default {
  name: 'Home',
  components: {
    ROCDatePick
  },
  data () {
    return {
      ROCDate: "110-11-11"
    }
  }
}
</script>
