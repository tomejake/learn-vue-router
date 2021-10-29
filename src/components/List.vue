<template>
  <div>
      <router-link to="/detail/0"><h5>{{blogData[0].title}}</h5></router-link>
      <p>{{blogData[0].date}}</p>
  </div>
  <div>
      <router-link to="/detail/1"><h5>{{blogData[1].title}}</h5></router-link>
      <p>{{blogData[1].date}}</p>
  </div>
  <div>
      <router-link to="/detail/2"><h5>{{blogData[2].title}}</h5></router-link>
      <p>{{blogData[2].date}}</p>
  </div>
</template>

<script>
export default {
  name : 'List',
  props : {
    blogData : Object,
  }
}
</script>

<style>

</style>