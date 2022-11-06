<template>
    <div class="Content" id="About">
         <div class="divider">a</div>
        <article>
            <h1>about me</h1>
            <div class="flex-content">
                <div class="flex-item-right">
                     <img src="../img/dummy_picture.webp" width="450px" height="530px" class="responsive">
                </div>
                <div class="flex-item-left">
                     <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores dolor esse maxime et sunt vitae sequi dolores delectus cum quibusdam!</p>
                      <h3>Skills</h3>
                        <div class="GroupImg">
                            <div class="rows">
                                <img src="../img/html.png"  width="120px" height="120x">
                                <img src="../img/css.png"   width="120px" height="120x">
                                <img src="../img/js.png"    width="120px" height="120x">
                                <img src="../img/node.jpg"  width="120px" height="120x">
                            </div>
                        
                            <div class="rows">
                                <img src="../img/php.png"    width="120px" height="120x">
                                <img src="../img/vscode.jpg" width="120px" height="120x">
                            </div>
                        </div>
                </div>
            </div>
           


        </article>
    </div>
</template>

<script>
export default {
    name:'MeAbout',
    component:{

    }
}
</script>

<style scoped>
.divider{
 margin: auto;
 margin-bottom:80px;
 background: #333;
 color: #333;
 width: 100%;

}
.Content{
    width: 80%;
    margin:auto;
    margin-bottom: 50px;
    padding: 10px;
}

h3{
    font-size:30px;
    margin-top: 50px;

}

article{
    height: 80%;
    margin:auto;
    text-align: center;
    margin-bottom: 400px;
    
}
.GroupImg{
    width:100%;
    border:1px solidrgb(231, 3, 3); 
    box-sizing:border-box;
    padding: 10px;

}

.rows img{
    padding: 5px;
    border-radius: 50%;
}

.flex-content{
    margin:30px;
    display:flex;
    flex-direction:row;
    text-align: center;
}
.flex-item-left{
    padding:20px;
    flex:50%;
}
.flex-item-right{
    padding:10px;
    flex:50%;
}


@media(max-width: 800px){
    .flex-content{
        flex-direction:column;
    }
    .responsive{
    width:100%;
    max-width:400px;
    height: auto;
    }
    .Content{
    width: 100%;
}
}
</style>