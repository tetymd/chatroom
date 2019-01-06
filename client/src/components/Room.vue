<template>
  <div class="room">
    <p class="title">room 1</p>
  </div>
</template>

<script>
export default {
  name: 'room'
}
</script>

<style lang="scss">
body {
}
.room {
  width: 20%;
  height: 200px;
  margin: 2em auto 2em auto;
  background: #f1f1f1;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.22);
}
.room .title {
  font-size: 1.2em;
  background: #5fc2f5;
  padding: 4px;
  text-align: center;
  color: #FFF;
  font-weight: bold;
  letter-spacing: 0.05em;
}
.room p {
  padding: 15px 20px;
  margin: 0;
}
</style>
