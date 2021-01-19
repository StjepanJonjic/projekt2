<template >
  <nav>
      <div class="topnav">
          <a><router-link class="active" to="/" exact>Naslovna</router-link></a>

  <div class="topnav-right">
      <a><router-link to="/login" exact>Prijava</router-link></a>
      <a><router-link to="/register" exact>Registracija</router-link></a>
    
  </div>
  </div>

    
  </nav>
</template>

<script>

export default{

}

</script>

<style scoped>
.topnav {
    background-color: #333;
    overflow: hidden;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #4CAF50;
  color: white;
}

.topnav-right {
  float: right;
  background-color: #4CAF50;
  color: white;
  
}


</style>