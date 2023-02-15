<script>
export default {
    name: 'AppMainSectionSix'
}
</script>

<template>
    <div class="section-six">
        <div class="container pt-5 pb-5">
            <div class="row text-center">
                <div class="col">
                    <h6>
                        Read for more joyment
                    </h6>
                </div>
            </div>

            <div class="row text-center">
                <div class="col">
                    <h2>
                        Latest from <span class="span">Our Blogs</span>
                    </h2>
                </div>
            </div>
            <div class="row">
                <div class="col d-flex justify-content-center">
                    <div class="card " style="width: 18rem;">
                        <img src="./assets/artist-blog-03-480x325.jpeg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Artist</h5>
                            <p class="card-text">Brush Strokes Energize Trees in Paintings</p>
                            <div class="d-flex">
                                <div class="w-50">
                                    <i class="fa-regular fa-file-lines"></i>20 Lessons
                                </div>
                                <div class="w-50">
                                    <i class="fa-regular fa-user"></i>50 students
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card ms-5 me-5" style="width: 18rem;">
                        <img src="./assets/artist-blog-01-480x325.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Artist</h5>
                            <p class="card-text">Pocket-sized Notebooks Hold Miniature Paintings</p>
                            <div class="d-flex">
                                <div class="w-50">
                                    <i class="fa-regular fa-file-lines"></i>20 Lessons
                                </div>
                                <div class="w-50">
                                    <i class="fa-regular fa-user"></i>50 students
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card" style="width: 18rem;">
                        <img src="./assets/artist-blog-02-480x325.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Artist</h5>
                            <p class="card-text">Connection Between Self-Portraits and Identity</p>
                            <div class="d-flex">
                                <div class="w-50">
                                    <i class="fa-regular fa-file-lines"></i>20 Lessons
                                </div>
                                <div class="w-50">
                                    <i class="fa-regular fa-user"></i>50 students
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.section-six {
    background-color: #f1f5ed;
    margin-top: 200px;

    h6 {
        text-transform: uppercase;
        font-size: .9rem;
    }

    .span {
        color: #20ad96;
    }

    .card-title {
        font-size: 1rem;
    }

    .card-text {
    font-weight: bold;
    }

    .w-50 {
        font-size: 0.8rem;
        color: #696969;

        i {
            margin-right: 5px;
        }
    }

    .card:hover {
        cursor: pointer;
        color: #20ad96;
    }

}
</style>