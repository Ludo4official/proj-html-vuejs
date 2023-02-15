<script>
export default {
    name: 'AppFooter',

    data() {
        return {
            explores: [
                'Start Here',
                'Blog',
                'About us',
                'Success story',
                'Courses',
                'Contact us'
            ],
            infos: [
                'Membership',
                'Purchase guide',
                'Privacy policy',
                'Terms of service'
            ]
        }
    }
}
</script>

<template>
    
    <div class="footer">
        <div class="container">
            <div class="row pt-5">
                <div class="col-6">
                    <div class="fw-bold">
                        Address
                    </div>
                    <ul>
                        <li>
                            382 NE 191st St # 87394 Miami, FL 33179- 3899
                        </li>
                        <li>
                            +1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)
                        </li>
                        <li>
                            support@maxcoach.com
                        </li>
                    </ul>
                    <div class="icons">
                        <i class="fa-brands fa-square-facebook"></i>
                        <i class="fa-brands fa-twitter"></i>
                        <i class="fa-brands fa-instagram"></i>
                        <i class="fa-brands fa-linkedin-in"></i>
                    </div>
                </div>
                <div class="col-3">
                    <div class="fw-bold">
                        Explore
                    </div>
                    <ul>
                        <li v-for="explore in explores">
                            {{ explore }}
                        </li>
                    </ul>
                </div>
                <div class="col-3">
                    <div class="fw-bold">
                        Information
                    </div>
                    <ul>
                        <li v-for="info in infos">
                            {{ info }}
                        </li>
                    </ul>
                </div>
            </div>
            <div class="row text-center mt-5">
                <div class="col">
                    <i class="fa-regular fa-copyright"></i> 2020 Maxcoach. All Rights Reserved
                </div>
            </div>
            <div>
                <a href="#">
                    <i class="fa-solid fa-arrow-up-long"></i>
                </a>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.footer {
    background-color: #3f3a64;
    min-height: 300px;
    margin-top: 200px;
    color: wheat;
    position: relative;

    ul {
        list-style: none;
        padding: 20px 0px;
        
        li {
            text-decoration: none;
            font-size: 0.8rem;
        }
    }

    a {
        position: absolute;
        bottom: 5%;
        right: 10%;
        background-color: #20ad96;
        color: white;
        border-style: none;
        border-radius: 50%;
        line-height: 50px;
        height: 50px;
        width: 50px;
        text-align: center ;
    }

    .icons {
        color: #f5f1ed;
        font-size: 1.2rem;

        i {
            padding: 0px 10px;

            &:hover {
                cursor: pointer;
                color: #20ad96;
            }
        }
    }
}

</style>
