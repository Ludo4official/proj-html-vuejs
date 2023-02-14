<script>
export default {
    name: 'AppJumbo'
}
</script>

<template>
    <div class="img-bg">
        <div class="jumbo">
            <div class="title">
                <h3>
                    TITOLO
                </h3>
            </div>
            <div class="mega-title">
                <h1>
                    MEGA TITOLO
                </h1>
            </div>
            <div class="link">
                <a href="#">BUTTON</a>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>

.img-bg {
    min-height: 500px;
    background-image: url(./assets/home-3-hero-bg.jpg);
    background-size: auto;
    width: 100%;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;

    .jumbo {
        width: 100%;
        border-style: dashed;

        .title, .mega-title, .link {
            text-align: center;
            color: white;

            a {
                color: blue;
                text-decoration: none;
                background-color: white;
                padding: 5px 40px;
            }
        }
    }
}

</style>