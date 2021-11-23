<template>
  <div id="app" class="ab-container">
    <div class="ab-contain">
      <img alt="Vue logo" src="./assets/logo.png">
      <Title />
      <Main />
    </div>
  </div>
</template>

<script>
import Title from "./components/Title.vue"
import Main from "./components/Main.vue"

export default {
  name: 'App',
  components: {
    Title,
    Main
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.ab-container{
  width: 100%;
  height: 100vh;
  background-color: aquamarine;
  display: flex;
  justify-content: center;
  align-content: center;
  align-items: center;
}

.ab-contain{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 600px;
  height: 800px;
  background-color: white;
  border-radius: 10px;
  border: 2px solid black;
}

img{
  width: 300px;
}
</style>
