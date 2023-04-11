<template>
<head>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>
<SetHeader />
  <TopIndex />
  <SetFooter />
</template>

<script>
import SetHeader from '@/components/Common/SetHeader.vue'
import SetFooter from '@/components/Common/SetFooter.vue'
import TopIndex from '@/components/TopIndex.vue'

export default {
  name: 'App',
  components: {
    SetFooter,
    TopIndex,
    SetHeader
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
