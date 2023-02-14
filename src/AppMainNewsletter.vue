<script>
export default {
    name: 'AppMainNewsletter'
}
</script>

<template>
    <div class="row mt-5">
        <div class="col">
            <h2>
                TESTO
            </h2>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Veniam aut velit, voluptate quisquam laudantium deleniti voluptatum.
            </p>
        </div>
    </div>
    <div class="row mb-5">
        <div class="col">
            <input type="text" name="" id="" placeholder="Enter your email">
            <button></button>
        </div>
    </div>

    <img class="img-one" src="./assets/maxcoach-shape-09.png" alt="">
    <img class="img-two" src="./assets/maxcoach-shape-02.png" alt="">
</template>

<style lang="scss" scoped>
.img-one, .img-two {
    position: absolute;
}

.img-one {
    top:0;
    right: 0;
}

.img-two {
    top: 80%;
    right: 0;
}
</style>