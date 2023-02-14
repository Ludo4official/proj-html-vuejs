<script>
export default {
    name: 'AppMainSectionFour'
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
        <div class="col-7 position-col">
            <div class="principal-card">
                <h3>
                    TESTO
                </h3>
                <p class="mt-5">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente, molestias exercitationem provident amet ducimus voluptatibus inventore cum soluta aperiam consequuntur?
                </p>
                <div class="employee mt-5">
                    <img src="./assets/testimonial-avata-01.jpg" alt="">
                    <div class="ms-4">
                        <div class="mb-3">
                            NOME
                        </div>
                        <div>
                            MESTIERE
                        </div>
                    </div>
                </div>
            </div>
            <div class="secondary-card">
                <h3>
                    TESTO
                </h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente, molestias exercitationem provident amet ducimus voluptatibus inventore cum soluta aperiam consequuntur?
                </p>
            </div>
            <div class="secondary-card-two">
                <div class="employee">
                    <img src="./assets/testimonial-avata-01.jpg" alt="">
                    <div class="ms-4">
                        <div class="mb-3">
                            NOME
                        </div>
                        <div>
                            MESTIERE
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.my-row {
    margin-top: 150px;
    min-height: 300px;

    .position-col {
        position: relative;
        display: flex;
        justify-content: center;

        .principal-card {
            box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.62);
            padding: 20px;
            background-color: white;

            .employee {
                display: flex;
                height: 70px;

                img {
                    border-radius: 50%;
                }
            }
        }
        
        .secondary-card {
            position: absolute;
            height: 100px;
            opacity: 0.3;
            top: -30%;
            width: 80%;
            z-index: -1;
            box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.62);
            padding: 20px;
            background-color: white;
        }

        .secondary-card-two {
            position: absolute;
            opacity: 0.3;
            top: 100%;
            width: 80%;
            z-index: -1;
            box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.62);
            padding: 20px;
            background-color: white;

            .employee {
                display: flex;
                height: 70px;

                img {
                    border-radius: 50%;
                }
            }
        }
    }
}

</style>