<script>
export default {
    name: 'AppMainSectionTwo'
}
</script>

<template>
    <div class="row my-row">
        
        <div class="col-7">
            <div class="bg-img">
                <img class="imgOne" src="./assets/maxcoach-shape-05-100x100.png" alt="">
                <img class="imgTwo" src="./assets/icon-youtube-play.png" alt="">
                <img class="imgThree" src="./assets/maxcoach-shape-07-150x150.png" alt="">
            </div>
        </div>

        <div class="col-5 ps-5">
            <p class="first-p">
                How we work
            </p>
            <h3>
                Upgrade Your Skills <span>Upgrade Your Life</span>
            </h3>
            <p>
                Opening up more opportunities in front of you to get the ticket to more enjoyable door in life. Getting equipped with new skills for new sets of insights into your career. MaxCoach accompany learners in every stage of learning.
            </p>
            <p class="fw-bold">
                Download free guidebook <i class="fa-solid fa-arrow-right-long"></i>
            </p>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.my-row {
    margin-top: 150px;
    min-height: 300px;

    .first-p {
        text-transform: uppercase;
    } 

    h3 {
        font-weight: bold;
        font-size: 2.35rem;

        span {
            color: #20ad96;
        }
    }

    .bg-img {
        background-image: url(./assets/stock-full-hd-11-670x450.jpg);
        background-repeat: no-repeat;
        height: 100%;
        background-size: cover;
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
            top: 50%;
            left: 50%;
            width: 70px;
            transform: translate(-50%, -50%);

        }

        .imgThree {
            position: absolute;
            bottom: -20%;
            right: -5%;
            z-index: -1;
        }
    }
}

.my-row-2 {
    margin-top: 150px;
    text-align: center;
}

</style>