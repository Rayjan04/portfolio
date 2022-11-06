<template>
    <div id="Home">
        <section>
             <div class="divider">a</div>
            <div class="HomeContent">
                <div class="Content">
                    <h3>Hi, my name is</h3>
                     <h1>Rayjan Mojillo</h1>
                     <h2>A Web Developer</h2>
                     <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ex, deserunt sequi! Fugit earum, praesentium ad deleniti similique odio illo distinctio!</p>
                    <button>Download  CV</button>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name:'SectionM',
    components:{
    
    }
    
}

</script>

<style scoped>
.divider{
 margin: auto;
 margin-bottom:100px;
 background: #333;
 color: #333;
 width: 80%;

}

*{
    
    padding:0;
    margin:0;
    padding:0;
}
.HomeContent{
    width:80%;
    margin:auto;
    margin-bottom: 500px;
}

.Content{
    
    margin:200px 50px 30px 50px ;
}

.Content h3{
    font-weight: 300;
    
}
.Content h1{
    font-weight: bold;
    font-size: 50px;
    color:#333;
}
.Content h2{
    font-weight: 700;
    font-size:35px;
    padding:10px;
    color:#333;
    text-transform:uppercase;
}
.Content p{
    width: 80%;
}

.Content button{
    margin-top:20px;
    background-color:#333;
    color:#ffff;
    padding:15px 15px;
    border:none;
    cursor: pointer;
}

@media (max-width: 800px) {
    .HomeContent{
        width:100%;
    }
    .Content p{
        width: 100%;
    }
    .Content h1{
    font-weight: bold;
    font-size: 45px;
    }
}


</style>