<template>
  <div>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'Message',
  data() {
    return {
      msg: 'Main branch!!!',
    };
  },
};
</script>

<style scoped>
p {
  color: blue;
  font-size: 36px;
}

div {
  background-color: yellow;
}
</style>