<template>
  <div>
    <flip-countdown deadline="2019-12-25 00:00:00"></flip-countdown>
  </div>
</template>

<script>
  import FlipCountdown from 'vue2-flip-countdown'

  export default {
      components: { FlipCountdown }
  }
</script>