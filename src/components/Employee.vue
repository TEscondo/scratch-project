<template>
  <div class = 'info'>
      My name is {{name}} and I am a {{job}}.
  </div>    
</template>

<script>
export default {
    name: 'employee',
    data() {
        return {
            name: 'Kaiba',
            job: 'Duelist'
        }
    }
}
</script>

<style>
    .info {
        color : red;
    }
</style>