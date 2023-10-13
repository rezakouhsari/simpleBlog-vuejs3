<template>
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-6">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem
          totam, ratione, voluptas eveniet soluta incidunt itaque optio beatae
          id temporibus, ex exercitationem sint ad earum in sed? Quam, cum sunt.
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem
          totam, ratione, voluptas eveniet soluta incidunt itaque optio beatae
          id temporibus, ex exercitationem sint ad earum in sed? Quam, cum sunt.
        </p>

        <router-link class="btn btn-dark" :to="{name:'users'}">Users</router-link>
        <router-link class="btn btn-light ms-3" :to="{name:'posts'}">Posts</router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>