<script>
export default {
    name: 'AppMainSectionFive'
}
</script>

<template>
    <div class="row my-row">
        
        <div class="col-7">
            <div class="bg-img">
                <img class="imgOne" src="./assets/maxcoach-shape-05-100x100.png" alt="">
                <img class="imgTwo" src="./assets/maxcoach-shape-01.png">
                <img class="imgThree" src="./assets/maxcoach-shape-07-150x150.png" alt="">
            </div>
        </div>

        <div class="col-5 ps-5">
            <p class="first-p">
                everything in <span class="fw-bold">maxcoach</span>
            </p>
            <h3 class="mt-5">
                We're Here To <span>Transform</span> You!
             </h3>
            <p class="mt-5">
                As learners, people can enjoy great companionship from MaxCoach mentors and educators. We can help you develop and grow at your best.
            </p>
            <a href="#">Get Free Guide</a>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.my-row {
    margin-top: 250px;
    min-height: 500px;

    .first-p {
        text-transform: uppercase;

    }

    h3 {
        font-weight: bolder;
        font-size: 2.5rem;

        span {
            color: #20ad96;
        }
    }
    
    a {
        color: white;
        text-decoration: none;
        background-color: #20ad96;
        padding: 10px 40px;
        border-radius: 10px;
        font-weight: bold;

        &:hover {
            background-color: black;
            color: #20ad96;
        }
    }

    .bg-img {
        background-image: url(./assets/home-3-team-image.png);
        background-repeat: no-repeat;
        height: 100%;
        width: 100%;
        background-size: auto;
        position: relative;
        border-radius: 10px;

        .imgOne {
            width: 150px;
            position: absolute;
            top: 10%;
            left: -15%;
            border-radius: 10px;
            z-index: -1;
        }

        .imgTwo {
            position: absolute;
            bottom: 0;
            left: -20%;
            width: 70px;
        }

        .imgThree {
            position: absolute;
            bottom: -20%;
            right: 45%;
            z-index: -1;
        }
    }
}

</style>