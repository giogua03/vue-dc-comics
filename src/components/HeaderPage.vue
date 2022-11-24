<template>
  <header>
    <img src="img/dc-logo.png" alt="">
    <nav>
      <ul>
        <li><a href="">CHARACTERS</a></li>
        <li><a href="">COMICS</a></li>
        <li><a href="">MOVIE</a></li>
        <li><a href="">TV</a></li>
        <li><a href="">GAMES</a></li>
        <li><a href="">COLLECTIBLES</a></li>
        <li><a href="">VIDEOS</a></li>
        <li><a href="">FANS</a></li>
        <li><a href="">NEWS</a></li>
        <li><a href="">SHOP</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
    name: 'HeaderPage',
}
</script>

<style lang="scss" scoped>
  header {
    text-align: center;
    display: flex;
    justify-content: space-around;
    height: 70px;
    margin-top: 1rem;
    margin-bottom: 1rem;
    nav {
      height: 3rem;
      ul {
        display: flex;
        justify-content: center;
        height: 100%;
        list-style: none;
        margin-top: .5rem;
        a {
          display: flex;
          justify-content: center;
          align-items: center;
          padding: 0 .5rem;
          height: 100%;
          &:hover {
            background-color: aquamarine;
          }
        }
      }
    }
  }
</style>
