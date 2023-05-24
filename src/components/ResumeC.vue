<template>
    <div class="container resume">
        <div class="row">
            <div class="col-lg-3 p-3 experience">
                <h3>Experience</h3>
                <ul>
                    <li>
                        <h5>Intern Full Stack Software Developer</h5>
                        <h6>LC Studio</h6>
                        <p>Duration : Currently</p>
                    </li>
                    <li>
                        <h5>Intern IT Support</h5>
                        <h6>Oaklands Secondary School</h6>
                        <p>Duration : 2022</p>
                    </li>
                    <li>
                        <h5>Intern HR Administrator</h5>
                        <h6>Disabled People South Africa</h6>
                        <p>Duration : 2019 - 2020</p>
                    </li>
                    <li>
                        <h5>General Assistant</h5>
                        <h6>PEP Stores</h6>
                        <p>Duration : 2017 - 2018</p>
                    </li>
                </ul>
            </div>
            <div class="col-lg-3 p-3 education">
                <h3>Education</h3>
                <ul>
                    <li>
                        <h5>Full Stack Software Development</h5>
                        <h6>Life Choices Coding Academy</h6>
                        <p>Duration : 2022 - 2023</p>
                    </li>
                    <li>
                        <h5>CISCO IT Specialist</h5>
                        <h6>College of Cape Town (Crawford)</h6>
                        <p>Duration : 2021</p>
                    </li>
                    <li>
                        <h5>Business Administration</h5>
                        <h6>Siyaya Skills Institute</h6>
                        <p>Duration : 2018 - 2020</p>
                    </li>
                    <li>
                        <h5>National Senior Certificate</h5>
                        <h6>Rocklands Secondary School</h6>
                        <p>Duration : 2012 - 2016</p>
                    </li>
                </ul>
            </div>
            <div class="col-lg-5 p-3 skills text-center justify-content-center">
                <h3>Skills</h3>
                <h5>Tech Stack</h5>
                <ul>
                    <li>
                        <img src="https://i.postimg.cc/Lsjcvqs6/html-5-v1.png" alt="">
                    </li>
                    <li>
                        <img src="https://i.postimg.cc/wv7hgNs9/CSS3-logo-svg.png" alt="">
                    </li>
                    <li>
                        <img src="https://i.postimg.cc/2SHSzZx9/Java-Script-logo.png" alt="">
                    </li>
                    <li>
                        <img src="https://i.postimg.cc/SxND2JBz/Bootstrap-logo-svg.png" alt="">
                    </li>
                    <li>
                        <img src="https://i.postimg.cc/15M8tt0T/Vue-js-Logo-2-svg.png" alt="">
                    </li>
                    <li>
                        <img src="https://i.postimg.cc/XJ55G8HY/mysql.png" alt="">
                    </li>
                    <li>
                        <img src="https://i.postimg.cc/cCcYcBpM/2560px-Node-js-logo-svg.png" alt="">
                    </li>
                    <li>
                        <img src="https://i.postimg.cc/vBS71bh6/Wordpress-Blue-logo.png" alt="">
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.skills ul{
    list-style: none;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    padding: 20px auto;
}
.resume{
    min-height: 80vh;
    display: flex;
    align-items: center;
}

h3{
    padding: 20px 0;
}

.skills li{
    margin: 20px 20px 20px 0;
    padding: 5px;
    filter: grayscale();
    cursor: pointer;
}

.skills li:hover{
    filter: none;
}

.skills ul{
    display: flex;
    justify-content: center;
}

.skills img{
    width: 4rem;
}

.education,.experience{
    border: 1px solid rgba(128, 128, 128, 0.093);
    box-shadow: 3px 3px 3px grey;
    margin: 10px;
    cursor: pointer;
}

.education:hover,.experience:hover{
    background-color: #B9AA87;
    color: white;
}

@media screen and (max-width:640px){
    .education,.experience{
        font-size: smaller;
        text-align: justify;
        box-shadow: none;
        border: none;
    }
    .education:hover,.experience:hover{
    background-color: white;
    color: black;
}
}

@media screen and (max-width:425px){
    .education,.experience{
        font-size: small;
    }
    h3,h5,h6{
        font-size: medium;
    }
}
</style>