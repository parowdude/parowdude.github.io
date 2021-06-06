<template>
  <div id="app">
    <div id="nav">
        <router-link to="/">Home</router-link> | 
        <router-link to="/crypto">Crypto</router-link> | 
        <router-link to="/stuff">Stuff</router-link> | 
        <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
    width: 100%;
    height: 100%;
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    background-color: #2c3e50;
    color: wheat;
}

#nav {
    padding: 30px;
    height: 8%;
    a
    {
        font-size: x-large;
        font-weight: bold;
        color: wheat;
        &.router-link-exact-active
        {
        color: #42b983;
        }
    }
}
</style>
