<template>  
  <div class="NavContent">
    <nav> 
      <div class="Logo" >
        <input type="checkbox" id="check">
            <label for="check" class="checkbtn"  >
              <i class="fa fa-bars" ></i>
            </label>
         <label> <img src="../img/Rj.jpg"  width="80px" height="80px"></label>
        <ul > 
          <li><a href="#Home" class="active">Home</a></li>
          <li><a href="#Projects">Project</a></li>
          <li><a href="#About">About</a></li>
          <li><a href="#Contact">Contact</a></li>
        </ul>
      </div>
    </nav>
    </div>    
</template>


<script>

export default {
  name: 'NavBar',
  components: {
    
  }
}
</script>

<style scoped>
*{
  /* reset all */
  padding:0;
  margin:0;
  text-decoration: none;
  list-style:none;
  Box-sizing: border-box;
  
}
.NavContent{
  /* setnavbar color and size */
  background:#ffff;
  width: 100%;
  margin: auto;
  position: fixed;
  
  top:0;
  

}
.Logo label{
  /* logo design */
  color: black;
  font-size: 35px;
  font-weight: bold;
  line-height: 80px;
  padding-left:30px;
}

nav ul{
  /* List tag position */
  float:right;
  padding-right: 50px;
}
nav ul li{
  /* modify tag list */
  display:inline-block;
  line-height:80px;
  margin-left:50px;
}
nav ul li a{
  /* lis tag colos set */
  color:black;
  font-size:17px;
}
a.active,a:hover{
  /* hover for responsive list */
  transition:.5s;
}

/* checl button */
.checkbtn{
  font: size 30px;
  color:#ffff;
  float:right;
  line-height:80px;
  margin-right:10px;
  cursor:pointer;
  display: none; 
}
#check{
   display:none;  
}

/* Media Queries  for responsiveness */
@media (max-with: 600px){
  .logo label{
    font: 30px;
    padding-left :50px;
  }
  nav ul li a{
    font-size:16px;
  }
}

@media (max-width: 800px){
 .checkbtn{
    display: block; 
  }
    ul{
    position: fixed;
    width: 100%;
    height:100vh;
    background:#ffff;
    top:80px;
    left:-100%;
    text-align:center;
    transition: all .4s;
  }
  nav ul li{
    display:block;
    margin:50px;
    line-height:30px;

  }
  nav ul li a{
    font-size: 20px;
  }
  a:hover,a.active{
    background:none;
    color:#020b11;
  }
  #check:checked ~ ul{
    left :0;
  }
  .Logo label{
  /* logo design */
  color: black;
  line-height: 80px;
  padding-left:0px;
}
}
</style>