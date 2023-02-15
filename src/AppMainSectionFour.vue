<script>
export default {
    name: 'AppMainSectionFour'
}
</script>

<template>
    <div class="row my-row">
        <div class="col-5">
            <p class="first-p">
                testimonials
            </p>
            <h3 class="first-title">
                Why Do People <span>*Hearts*</span> Us?
            </h3>
            <p>
                Seeking for verbals of our service quality? Find them here. Everything is transparent and straightforward for your sense of justification.
            </p>
            <p class="fw-bold">
                View all <i class="fa-solid fa-arrow-right-long"></i>
            </p>
        </div>
        <div class="col-7 position-col">
            <div class="principal-card">
                <h3>
                    Professional team of specialists and passionate mentors at reach
                </h3>
                <p class="mt-5">
                    I need to get a certification for English proficiency and MaxCoach is my best choice. Their tutors are smart and professional when dealing with students.
                </p>
                <div class="employee mt-5">
                    <img src="./assets/testimonial-avata-01.jpg" alt="">
                    <div class="ms-4">
                        <div class="mb-3">
                            MADLEY PONDOR
                        </div>
                        <div>
                            / IT SPECIALIST
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
                    <img src="./assets/testimonial-avata-02.jpg" alt="">
                    <div class="ms-4">
                        <div class="mb-3">
                            MINA HOLLACE
                        </div>
                        <div>
                            / Freelancer
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

    .first-p {
        text-transform: uppercase;
    }

    .first-title {
        font-weight: bold;
        font-size: 2.5rem;

        span {
            color: #20ad96;
        }
    }

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