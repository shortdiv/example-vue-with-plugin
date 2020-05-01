<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
ul {
  list-style: none;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
body,
html {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}
a {
  text-decoration: none;
}
button {
  width: 100%;
  padding: 20px 60px;
  outline: none;
  background-color: #282c34;
  border: none;
  border-radius: 5px;
  box-shadow: 0 9px #95a5a6;
  font-size: 1.2em;
  color: white;
  &:hover {
    cursor: pointer;
  }
}
</style>