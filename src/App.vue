<script>
import Clock from '@/components/Clock'

export default {
  components: {
    Clock
  }
}
</script>

<template>
    <div>
        <Clock class='clock'/>
    </div>
</template>

<style scoped>
.clock {
    width: 100%;
    max-width: 500px;
    margin: 30px auto;
}
</style>
<style>
html {
    font-size: 62.5%;
}

body {
    margin: 0;
}

p{
    margin:0;
}
</style>
