<template>
  <div>
      <h5><router-link to="/detail">{{blogData[0].title}}</router-link><br></h5>
      <p>{{blogData[0].date}}</p>
  </div>
  <div>
      <h5><router-link to="/detail">{{blogData[1].title}}</router-link><br></h5>
      <p>{{blogData[1].date}}</p>
  </div>
  <div>
      <h5><router-link to="/detail">{{blogData[2].title}}</router-link><br></h5>
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