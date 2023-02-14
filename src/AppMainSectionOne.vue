<script>
export default {
    name: 'AppMainSectionOne'
}
</script>

<template>
    <div class="row my-row">
        <div class="col-5">
            <p>
                TESTO
            </p>
            <h3>
                TITOLO
            </h3>
            <p>
                ALTRO TESTO
            </p>
            <p>
                Questions
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

    <div class="row">
        
    </div>
</template>

<style lang="scss" scoped>

.my-row {
    margin-top: 150px;
    min-height: 300px;

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

</style>