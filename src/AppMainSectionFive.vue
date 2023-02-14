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
            <p>
                TESTO
            </p>
            <h3>
                TITOLO
            </h3>
            <p>
                ALTRO TESTO
            </p>
            <a href="#">BUTTON</a>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.my-row {
    margin-top: 250px;
    min-height: 500px;

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

.my-row-2 {
    margin-top: 150px;
    text-align: center;
}

</style>