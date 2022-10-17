<template>
    <div>
        <article>
            <h1>about me</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores dolor esse maxime et sunt vitae sequi dolores delectus cum quibusdam!</p>
            <h3>Skills</h3>
            <div class="GroupImg">
                <div class="row">
                    <img src="img/img2.png" width="200px" height="150px">
                    <img src="img/img2.png" width="200px" height="150px">
                    <img src="img/img2.png" width="200px" height="150px">
                    <img src="img/img2.png" width="200px" height="150px">
                </div>
               
                <div class="row">
                    <img src="img/img2.png" width="200px" height="150px">
                    <img src="img/img2.png" width="200px" height="150px">
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
article{
    height: 80%;
    margin:auto;
    text-align: center;
    margin-bottom: 400px;
    
}
.GroupImg{
    width: 80%;
    margin:auto;
    border:1px solid#ccc;
    box-sizing:border-box;
    padding: 10px;
}

.row img{
    margin-left:8px;    
}

</style>