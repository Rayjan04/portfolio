<template>
<div class="Content" id="Contact">
    <div class="divider">a</div>
    <h1>Contact Me</h1>
    <form id="contact_form" name="contact_form" method="post">
        <div class="mb-5 row">
            <div class="col">
                <label>First Name</label>
                <input type="text" required maxlength="50" class="form-control" id="first_name" name="first_name">
            </div>
            <div class="col">
                <label>Last Name</label>
                <input type="text" required maxlength="50" class="form-control" id="last_name" name="last_name">
            </div>
        </div>
        <div class="mb-5 row">
            <div class="col">
                <label for="email_addr">Email address</label>
                <input type="email" required maxlength="50" class="form-control" id="email_addr" name="email"
                    placeholder="name@example.com">
            </div>
            <div class="col">
                <label for="phone_input">Phone</label>
                <input type="tel" required maxlength="50" class="form-control" id="phone_input" name="Phone"
                    placeholder="Phone">
            </div>
        </div>
        <div class="mb-5">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" name="message" rows="5"></textarea>
        </div>
        <button type="submit" class="btn btn-primary px-4 btn-lg">Post</button>
    </form>
</div>
    
</template>

<script>
export default {
    name:'FooterM',
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


}
.Content{
    width: 80%;
    /* height: 700px; */
    margin:auto;
    margin-bottom: 50px;
    /* border-style: dotted;  */ /*this is use to see the border */
    padding: 10px;
    margin-bottom: 400px;
}

@media(max-width: 800px){
    .divider{
    width: 100%;
    }
    .Content{
    width: 90%;
    }
}
</style>