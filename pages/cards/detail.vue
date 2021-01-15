<template>
  <div class="app">
    <Header />
    <b-card
      no-body
      style="max-width: 20rem"
      img-src="/img/c-o-group-worldchamps2018-splash.jpg"
      img-alt="Image"
      img-top
    >
      <template #header>
        <h4 class="mb-0">card name</h4>
      </template>

      <b-card-body>
        <b-card-title>Role</b-card-title>
        <!-- <b-card-sub-title class="mb-2">Card Sub Title</b-card-sub-title> -->
        <b-card-text> Some quick description </b-card-text>
      </b-card-body>

      <b-list-group flush>
        <b-list-group-item>Stats : atk, def, ...</b-list-group-item>
      </b-list-group>

      <b-card-body>
        <a href="#" class="card-link"> purchase</a>
        <!-- <a href="#" class="card-link">Another link</a> -->
      </b-card-body>

      <!-- <b-card-footer>This is a footer</b-card-footer> -->
      <!-- 
      <b-card-img
        src="https://placekitten.com/480/210"
        alt="Image"
        bottom
      ></b-card-img> -->
    </b-card>
  </div>
</template>

<style scoped>
.app {
  margin-top: 4%;
  margin-left: 1%;
}
</style>