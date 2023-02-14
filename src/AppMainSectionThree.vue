<script>
export default {
    name: 'AppMainSectionThree'
}
</script>

<template>
    <div class="row my-row">
        <div class="col text-center">
            <h4>
                TESTO
            </h4>
        </div>
    </div>
    <div class="row">
        <div class="col text-center">
            <h2>
                TESTO
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
                            <img src="..." class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card title</h5>
                                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                                </div>
                            </div>
                            <div class="card me-3" style="width: 18rem;">
                            <img src="..." class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card title</h5>
                                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                                </div>
                            </div>
                            <div class="card" style="width: 18rem;">
                            <img src="..." class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card title</h5>
                                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
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
                TESTO TESTO TESTO
            </p>
        </div>
    </div>
</template>

<style lang="scss" scoped>

.my-row {
    margin-top: 150px;
}

</style>