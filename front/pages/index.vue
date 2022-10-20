<template>
  <div>
    Hello World
  </div>
</template>

<script>
import Vue from "vue";

export default Vue.extend({
  name: 'IndexPage',
  data() {
    return {
      title: 'Home'
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: 'Home page',
          name: 'Home page',
          content: 'My web site',
        }
      ]
    }
  }
})
</script>
