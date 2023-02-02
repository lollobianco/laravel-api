<template>
  <div>

    <div class="d-flex flex-column align-items-center justify-content-center text-white my-5">
      <h1 class="text-white">Welcome in BooleFood</h1>
      <h4>Use navigation bar</h4>
    </div>

    <PostsList/>

  </div>
</template>

<script>
import PostsList from '../../../components/posts/PostsList.vue';

export default {
  name: 'PostsIndex',
  components: {
    PostsList
  }
}
</script>

<style>

</style>