<script>
export default {
    name: 'AppMainSectionThree'
}
</script>

<template>
    <div class="row my-row">
        <div class="col text-center">
            <h4>
                join maxcoach at best
            </h4>
        </div>
    </div>
    <div class="row">
        <div class="col text-center">
            <h2>
                Latest Online <span>Courses</span>
            </h2>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <div id="carouselExampleIndicators" class="carousel slide">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <div class="d-block d-flex justify-content-center py-5">
                            <div class="card me-3" style="width: 18rem;">
                            <img src="./assets/course-02-480x298.jpg" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">$40,00</h5>
                                    <p class="card-text">Learning to Write as a Professional Author</p>
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
                            <div class="card me-3" style="width: 18rem;">
                            <img src="./assets/stock-full-hd-03-480x298.jpg" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">$0,00</h5>
                                    <p class="card-text">Customer-centric Info-Tech Strategies</p>
                                    <div class="d-flex">
                                        <div class="w-50">
                                            <i class="fa-regular fa-file-lines"></i>24 Lessons
                                        </div>
                                        <div class="w-50">
                                            <i class="fa-regular fa-user"></i>769 Students
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="card" style="width: 18rem;">
                            <img src="./assets/stock-full-hd-04-480x298.jpg" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">$19,00</h5>
                                    <p class="card-text">Open Programming Courses for Everyone: Python</p>
                                    <div class="d-flex">
                                        <div class="w-50">
                                            <i class="fa-regular fa-file-lines"></i>17 Lessons
                                        </div>
                                        <div class="w-50">
                                            <i class="fa-regular fa-user"></i>62 Students
                                        </div>
                                    </div>
                                </div>
                            </div>

                        </div> 
                    </div>
                    <div class="carousel-item">
                        <div class="d-block">
                            ciao2
                        </div> 
                    </div>
                    <div class="carousel-item">
                        <div class="d-block">
                            ciao3
                        </div> 
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="text-danger">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="text-danger">Next</span>
                </button>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col text-center">
            <p>
                Control your personal preference settings to get notified about appropriate courses. <span class="fw-bold">View all courses <i class="fa-solid fa-arrow-right-long"></i></span>
            </p>
        </div>
    </div>
</template>

<style lang="scss" scoped>

.my-row {
    margin-top: 150px;

    h4 {
        text-transform: uppercase;
        font-size: 1rem;
    }
}

h2 {
    font-size: 2.5rem;

    span {
        color: #20ad96;
    }
}

.card-title {
    color: #20ad96;
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

</style>