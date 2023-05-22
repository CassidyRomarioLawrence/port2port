<template>
<div class="container landing d-flex align-items-center">
    <div class="row w-100">
        <div class="col-sm-6 p-3">
            <h6>Welcome to my Portfolio</h6>
            <h1>I'm, Cassidy Romario Lawrence</h1>
            <h3>Full Stack Software Developer</h3>
        </div>
        <div class="col-sm-6 my-auto text-center">
            <img src="https://i.postimg.cc/QCvLBvPw/24122199-bwink-msc-09-single-05.jpg" class="side-img" alt="">
        </div>
    </div>
</div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.landing{
    min-height: 90vh;
}

.side-img{
    width: 20rem;
}

@media screen and (max-width: 669px){
    .side-img{
        width: 15rem;
    }
}

@media screen and (max-width: 481px){
    .side-img{
        width: 13rem;
    }
    .landing{
        justify-content: center;
    }
}
</style>