<template>
  <h2 id="my-app">App</h2>
  <p id="teste">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum beatae eligendi optio consectetur. Reiciendis est blanditiis consequatur voluptatibus ratione sunt, amet consequuntur nisi a dolorem, et quidem explicabo, earum enim.</p>

  <header>
    <div class="wrapper">
      <nav>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/donay">Donay</router-link>
      </nav>
    </div>
  </header>

  <router-view></router-view>
</template>

<script>

</script>

<style scoped>
#my-app {
  background: aqua;
}

#teste {
  color: red;
}
</style>
