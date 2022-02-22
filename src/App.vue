<template>
    <the-header title='RememberMe'/>
  <the-recources></the-recources>
</template>


<script>
import TheHeader from '@/components/layouts/TheHeader';
import TheRecources from '@/components/learning-resources/TheRecources';

export default {
  components: {
    TheHeader,
    TheRecources
  }
}

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Roboto', sans-serif;
}

body {
  margin: 0;
}
</style>
