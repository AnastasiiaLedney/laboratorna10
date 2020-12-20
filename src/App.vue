<template>
   <nav class="navbar navbar-expand-lg navbar-light bg-light" style="background-color:;">
  <div class="container-fluid">
<router-link to="/" class="navbar-brand" > Додому </router-link>
   
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
            <router-link to="/about" class="nav-link active" aria-current="page"> про автора </router-link>
         
        </li>
      </ul>
    </div>
  </div>
</nav>


    <router-view></router-view>
</template>

<script>
export default {
    name:"App",
    data(){
        return{

        }
    }
}
</script>
<style scoped>

</style>