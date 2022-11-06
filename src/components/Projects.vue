<template >
    <div id="Projects" >
        <div class="divider">a</div>
        <article>
            <div class="ProjectContent">
                <h1>My Projects</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos assumenda sapiente quae, fugit rem nesciunt facilis cum? Excepturi, dolor omnis?</p>
              
                    <div class="flex-container">
                        <div class="flex-item-left">
                            
                            <img src="../img/Protect.png" alt="Protect" class="responsive-img">
                        </div>

                        <div class="flex-item-right">
                            <h1>Protect</h1>
                            <h4>HTML,  CSS,  JavaScript, Bootsrap, Firebase, Node.js </h4>
                            <p>a cloud-based supply chain management system and inventory application with monitoring system using rfid for warehouse promotech resources incorporated.</p>
                            <a href="https://protech-project-aef56.web.app/"><button>View Project</button></a>
                        </div>                          
                            
                    </div>
                 
                    <div class="flex-container">
                        <div class="flex-item-left">
                            <img src="../img/Porfolio.png"  alt="Protect" class="responsive-img">
                        </div>

                        <div class="flex-item-right">
                                <h1>Portfolio</h1>
                                <h4>HTML, CSS, Vue.js </h4>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis, sed.</p>
                                <a href="#"><button>View Project</button></a>
                        </div>
                    </div>

                    <div class="flex-container">
                        <div class="flex-item-left">
                            <img src="../img/PhpCrud.png"  alt="PHP CRUD" class="responsive-img">
                        </div>

                        <div class="flex-item-right">
                                <h1>PHP OOP CRUD FUNCTION</h1>
                                <h4>PHP, CSS, JavaScript, Bootsrap</h4>
                                <p>This project is my simple OOP with MVC model</p>
                                <a href="https://github.com/Rayjan04/PHP-OOP-CRUD-FUNCTION"><button>View Project</button></a>
                        </div>
                    </div>
       
            </div>    
        </article>
    </div>

</template>

<script>
export default {
    name:'projectList',
    components:{

    }
}
</script>

<style scoped>
.divider{
 margin: auto;
 margin-bottom:80px;
 background: #333;
 color: #333;
 width: 80%;
}

.ProjectContent{
    width: 80%;
    margin:auto;
    padding: 10px;
    margin-bottom: 400px;
}
button{
    background-color:#333;
    color:#fff;
    padding :10px 15px;
    border:none;
    cursor:pointer;
}

.flex-container{
    padding:20px;
    margin-top:50px;
    display: flex;
    flex-direction:row;
    text-align: center;
}
.flex-item-left{
    padding:10px;
    flex:50%;
    border-style:ridge;
   
}

.flex-item-right{
    padding:10px;
    flex:50;
}

.flex-item-right h1{    
   padding:10px;
   text-align: right;
   right:50px; 
   font-size: 25px;
}

.flex-item-right h4{
    padding:10px;
    color: rgb(204, 168, 123);
    font-weight: 80;
    text-align: right ;
    font-size: 20px;

}
.flex-item-right p{
    padding:10px;
    text-align: right;
    text-transform: capitalize;

}
.flex-item-right button{
    float: right;
}

.responsive-img{
    width: 100%;
    height: 100%;
    max-width: 700px;

}
/* Responsive layout - makes a one column layout instead of a two-column layout */
@media (max-width: 800px) {
  .flex-container {
    flex-direction: column;
  }
  .ProjectContent{
    width: 100%;
    margin:auto;
}
    .divider{
    width: 100%;
    }
}
</style>