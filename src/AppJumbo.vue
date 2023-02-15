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
                    Commence Business
                </h3>
            </div>
            <div class="mega-title">
                <h1>
                    Distant Mentoring Program
                </h1>
            </div>
            <div class="link">
                <a href="#">Download free guidebook<i class="fa-solid fa-arrow-right-long"></i></a>
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

        .title, .mega-title, .link {
            text-align: center;
            color: white;
            margin-top: 20px;

            a {
                color: #20ad96 ;
                text-decoration: none;
                background-color: white;
                padding: 10px 40px;
                border-radius: 10px;
                font-weight: bold;

                &:hover {
                    background-color: #20ad96;
                    color: white;
                }
            }
        }
    }
}

</style>