<template>

  <div class="header">
    <img src="../assets/header1.jpg" alt="header" width="1870" height="400">
    <div class="menu">
      <div class="menu-item">
        <div class="menu-text">
          About
        </div>
      </div>
      <div class="menu-item">
        <div class="menu-text">
          Project
        </div>
      </div>
      <div class="menu-item menu-center">
        Home
      </div>
      <div class="menu-item">
        <div class="menu-text">
          YouTube
        </div>
      </div>
      <div class="menu-item">
        <div class="menu-text">
          Contact
        </div>
        
         

          
      



      </div>
    </div> 
  </div>


  
</template>

<script>

export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};



</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
   
  .menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 10px;
  height: 60px;
  
}
.menu-item {
  flex: 1;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  position: -webkit-sticky;
  position: sticky;
}
.menu-text{
  font-size: 20px;
  color: #818181;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #080808;
  width: fit-content;
  position: -webkit-sticky;
  position: sticky;
}
.menu-text:hover {
  border-bottom: 2px solid #c278ff;
}
.menu-center {
  font-size: 36px;
  color: rgb(255, 255, 255);
}
.header {
  background-size: 100% 100%;
  background-attachment: fixed;
  background-color: black;
}


 
</style>

