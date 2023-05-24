<template>
<div class="container projects">
    <div class="row">
        <div class="col-sm-6 image-1">
        </div>
        <div class="col-sm-6 image-2">
        </div>
    </div>
    <div class="row">
        <div class="col-sm-4 image-3">
        </div>
        <div class="col-sm-4 image-4">
        </div>
        <div class="col-sm-4 image-5">
        </div>
    </div>
    <div class="row image-6">
    </div>
</div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .projects{
        min-height: 100vh;
    }

    .image-1,.image-2,.image-3,.image-4,.image-5,.image-6{
        background-position: center;
        background-size: cover;
        background-repeat: no-repeat;
        min-height: 30vh;
        cursor: pointer;
        border: 1.5px solid white;
        filter: grayscale();
    }
    .image-1{
        background-image: url(https://i.postimg.cc/DfBJ79G4/Screenshot-2023-05-12-090927.png);
    }
    .image-2{
        background-image: url(https://i.postimg.cc/sf7QbTPb/Screenshot-2023-05-12-091345.png);
    }
    .image-3{
        background-image: url(https://i.postimg.cc/GmRNJvWw/Screenshot-2023-05-12-084350.png);
    }
    .image-4{
        background-image: url(https://i.postimg.cc/NFLsMV8N/portfolio-1.png);
    }
    .image-5{
        background-image: url(https://i.postimg.cc/TPmsv8tZ/active.png);
    }
    .image-6{
        background-image: url(https://i.postimg.cc/k4zbdZDt/Screenshot-2023-05-12-091817.png);
    }
</style>