<template>
  <div class="d-flex flex-column align-items-center flex-md-row justify-content-md-around">
    <ul class="home__list text-center text-md-end">
      <li class="list__item">node-sass</li>
    </ul>
    <ul class="home__list text-center text-md-start">
      <li class="list__item">sass-loader</li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
    .home__list { 
      width: 40%;
      margin: 0;
      padding: 0;
      color: #35495e;
      list-style: none;

      .list__item {
        font-size: 1.2em;
      }
    }

    
</style>