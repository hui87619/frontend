<template>
  <div>
    <save-action :is-add="true" :is-test-case="true" />
  </div>
</template>

<script>
import SaveAction from '../components/SaveAction'

export default {
  name: 'TestcaseActionAdd',
  components: {
    SaveAction
  }
}
</script>
