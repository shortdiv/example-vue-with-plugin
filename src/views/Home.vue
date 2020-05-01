<template>
  <div class="home">
    <PollForm />
  </div>
</template>

<script>
// @ is an alias to /src
import PollForm from '@/components/PollForm.vue'

export default {
  name: 'Home',
  components: {
    PollForm
  }
}
</script>
