<template>
  <TheButton
    color="accent"
    v-bind="$attrs"
    v-on="$listeners"
  />
</template>
<script>
import TheButton from '~/components/General/Buttons/TheButton'
export default {
  components: {
    TheButton
  }
}
</script>
