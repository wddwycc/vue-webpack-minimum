<template>
<div id="app">
  <p>hello {{ who }}</p>
</div>
</template>

<script>
export default {
  name: 'app',
  data() {
    return {
      who: 'monk studio'
    }
  }
}
</script>
