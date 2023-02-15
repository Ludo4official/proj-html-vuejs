<script>
export default {
    name: 'AppMainNewsletter'
}
</script>

<template>
    <div class="row mt-5">
        <div class="col">
            <h2>
                Subscribe <span>Newsletter</span>
            </h2>
        </div>
    </div>
    <div class="row">
        <div class="col mt-5">
            <p class="fw-bold">
                Enter your email address to register to our Newsletter subscription delivered on a regular basis!
            </p>
        </div>
    </div>
    <div class="row mb-5">
        <div class="col mt-5">
            <input class="email" type="text" name="" id="" placeholder="Enter your email">
            <button class="subscribe">Subscribe</button>
        </div>
    </div>

    <img class="img-one" src="./assets/maxcoach-shape-09.png" alt="">
    <img class="img-two" src="./assets/maxcoach-shape-02.png" alt="">
</template>

<style lang="scss" scoped>

h2 {
    font-size: 2.5rem;

    span {
        color: #20ad96;
    }
}

.email {
    background-color: #f1f5ed;
    border-style: none;
    padding: 10px 20px;
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
    width: 50%;
}

.subscribe {
    padding: 10px 20px;
    border-style: none;
    background-color: #20ad96;
    color: white;
    font-weight: bold;
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;

    &:hover {
        background-color: black;
        color: #20ad96;
    }
}
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