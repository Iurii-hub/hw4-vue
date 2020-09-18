<template>
  <div>
    <!-- <h1>Home</h1> -->
    <img class="photo" src="../components/Photos/Homer.jpg" alt="Page must be reload">
    
    <div>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iusto sint excepturi cupiditate assumenda saepe minima et exercitationem 
        consequatur nesciunt qui fugiat maiores, expedita ab. Exercitationem similique repellendus soluta voluptate aut!
    </div>

    <div>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic, adipisci.
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  
}
</script>

<style>
.photo {
    width: 500px;
    border: 1px solid gray;
    display: block;
    margin: auto;
    
}

body {
    background-image: url(../components/Photos/wallpaper.jpg);
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
    width: 100%;
    color: white;
}

</style>
