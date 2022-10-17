<template>
    <div>
        <article>
            <div class="ProjectContent">
                <h1>My Projects</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos assumenda sapiente quae, fugit rem nesciunt facilis cum? Excepturi, dolor omnis?</p>
                <div class="ProjectList">
                     <h1>Protect</h1>
                     <img src="https://i.postimg.cc/7hjKgMQH/Screenshot-2022-10-08-161156.png" width="400px" height="240px">
                     <h4>HTML,  CSS,  JavaScript, Bootsrap, Firebase, Node.js </h4>
                     <p>a cloud-based supply chain management system and inventory application with monitoring system using rfid for warehouse promotech resources incorporated..</p>
                     <a href="https://protech-project-aef56.web.app/"><button>View Project</button></a>
                     
                </div>
                 <div class="ProjectList">
                     <h1>Project 2</h1>
                     <img src="https://i.postimg.cc/LsB4wxzW/Screenshot-2022-10-08-161432.png" width="400px" height="240vue px">
                     <h4>HTML, CSS, Vue.js </h4>
                     <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis, sed.</p>
                     <a href="#"><button>View Project</button></a>
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

.ProjectContent{
    width: 80%;
    /* height: 700px; */
    margin:auto;
    margin-bottom: 50px;
    /* border-style: dotted;  */
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
.ProjectList{
    /* display: inline-block; */
    position:relative;
    width: 100%;
    padding: 20px;
    box-sizing: border-box;
}

.ProjectList h1{
   position :absolute;
   right:50px;
}
.ProjectList h4{
    color: rgb(204, 168, 123);
    font-weight: 80;
    position:absolute;
    right:50px;
    top:50px;
    
}
.ProjectList p{
    text-transform: capitalize;
    width: 500px;
    position:absolute;
    right:50px;
    top:80px;
}
.ProjectList button{
    position:absolute;
    right:50px;
    top:170px;
}

</style>