<template>
  <div class="home">
    <h1>Κεντρο δημιουργικής απασχόλησης παιδιων</h1>
    <h2>Δωρεαν μεσω εσπα</h2>
    <p>για παιδιά 5 εως 12 ετών</p>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {

  },
};
</script>

<style lang="scss">
.home {
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background: var(--color-primary);
  color: var(--color-white);
}
</style>
