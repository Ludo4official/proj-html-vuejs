<script>
import AppJumbo from './AppJumbo.vue';
export default {
    name: 'AppHeader',
    components: {
        AppJumbo,
    },
    data() {
        return {
            links: [
                'Home',
                'Pages',
                'Courses',
                'Features',
                'Blog',
                'Shop'
            ]
        }
    }
}
</script>

<template>

<div class="header">
    <div class="my-cnt">
        <div class="links">
            <ul>
                <li v-for="link in links">
                    <a href="#">{{ link }}</a>
                </li>
            </ul>
        </div>

        <div class="logo">
            <img src="./assets/dark-logo.png" alt="MaxCoach">
        </div>

        <div class="user">
            <div class="icons" >
                <i class="fa-solid fa-cart-shopping"></i>
                <i class="fa-solid fa-user"></i>
            </div>
            <div class="search-bar">
                <input type="text" name="" id="" placeholder="Search...">
                <button><i class="fa-solid fa-magnifying-glass"></i></button>
            </div>
        </div>
    </div>
</div>

<AppJumbo></AppJumbo>


</template>

<style lang="scss" scoped>

.header {
    width: 100vw;
    height: 70px;
    display: flex;
    justify-content: center;


    .my-cnt {
        width: 90%;
        height: 100%;
        display: flex;

        .links, .user {
            width: 40%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;

            ul {
                list-style: none;
                display: flex;

                li a {
                    text-decoration: none;
                    color: #3f3a64;
                    padding: 0px 15px;
                    font-weight: bold;
                }
            }

            .icons {
                font-size: 1.25rem;
                color: #3f3a64;

                i {
                    padding: 0px 15px;
                    cursor: pointer;
                }
            }

            .search-bar {

                input, button {
                    background-color: #f5f1ed;
                    border-style: none;
                    padding: 10px 20px;

                    i {
                        color: #20ad96;
                    }
                }
                
            }
        }

        .logo {
            width: 20%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
        }
    }
}

</style>
