<template>
  <div class="d-flex flex-column align-items-start flex-md-row justify-content-md-around">
    <ul class="home__list text-center text-md-end">
      <li class="list__item">vue-router</li>
      <li class="list__item">bootstrap</li>
      <li class="list__item">core-js</li>
    </ul>
    
    <ul class="home__list text-center text-md-start">
      <li class="list__item">vuex</li>
      <li class="list__item">@popperjs/core</li>
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