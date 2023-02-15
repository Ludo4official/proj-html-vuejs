<script>
export default {
    name: 'AppMainSectionOne'
}
</script>

<template>
    <div class="row my-row">
        <div class="col-5">
            <p class="first-p">
                Everything in <strong>MaxCoach</strong>
            </p>
            <h2>
                Learn about our <span>Work Culture</span> at MaxCoach
            </h2>
            <p>
                Spend some time to visit our website or head office and discover our current courses, enrollment procedure, and registration deadline. We're opening new classes every beginning of each month.
            </p>
            <p>
                Have questions? <span class="questions">Get Free Guide<i class="fa-solid fa-arrow-right-long"></i></span>
            </p>
        </div>
        <div class="col-7">
            <div class="bg-img">
                <img class="imgOne" src="./assets/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg" alt="">
                <img class="imgTwo" src="./assets/maxcoach-shape-02.png" alt="">
                <img class="imgThree" src="./assets/maxcoach-shape-07-100x100.png" alt="">

            </div>
           
        </div>
    </div>

    <div class="row my-row-2">
        <div class="col-4">
            <div class="numbers">
                129+
            </div>
            <div class="text">
                enrolled learners
            </div>
        </div>
        <div class="col-4">
            <div class="numbers">
                80
            </div>
            <div class="text">
                finished sessions
            </div>
        </div>
        <div class="col-4">
            <div class="numbers">
                4%
            </div>
            <div class="text">
                satisfaction rate
            </div>
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

    h2 {
        font-weight: bolder;
        font-size: 2.35rem;

        span {
            color: #20ad96;
        }
    }

    .questions {
        color: #20ad96;
        font-weight: bold;
        cursor: pointer;
    }

    .bg-img {
        background-image: url(./assets/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg);
        background-repeat: no-repeat;
        height: 100%;
        background-size: cover;
        position: relative;
        border-radius: 10px;

        .imgOne {
            width: 150px;
            position: absolute;
            top: -25%;
            right: -10%;
            border-radius: 10px;
        }

        .imgTwo {
            position: absolute;
            top: 90%;
            right: 10%;
        }

        .imgThree {
            position: absolute;
            top: -20%;
            right: 5%;
            z-index: -1;
        }
    }
}

.my-row-2 {
    margin-top: 150px;
    text-align: center;

    .numbers {
        color: #20ad96;
        font-size: 3rem;
        font-weight: bold;
    }

    .text {
        text-transform: uppercase;
        font-weight: bold;
    }
}

</style>