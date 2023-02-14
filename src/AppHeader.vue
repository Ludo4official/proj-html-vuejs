<script>
import AppJumbo from './AppJumbo.vue';
export default {
    name: 'AppHeader',
    components: {
        AppJumbo,
    }
}
</script>

<template>

<div class="header">
    <div class="my-cnt">
        <div class="links">
            <ul>
                <li>
                    <a href="#">LINK</a>
                </li>
            </ul>
        </div>

        <div class="logo">
            LOGO
        </div>

        <div class="user">
            USER
        </div>
    </div>
</div>

<AppJumbo></AppJumbo>


</template>

<style lang="scss" scoped>

.header {
    width: 100vw;
    height: 70px;
    border-style: dashed;
    display: flex;
    justify-content: center;


    .my-cnt {
        width: 90%;
        height: 100%;
        border-style: dashed;
        display: flex;

        .links, .user {
            width: 40%;
            height: 100%;
            border-style: dashed;
            display: flex;
            align-items: center;
            justify-content: center;

            ul {
                list-style: none;

                li a {
                    text-decoration: none;
                    color: black;
                }
            }
        }

        .logo {
            width: 20%;
            height: 100%;
            border-style: dashed;
            display: flex;
            align-items: center;
            justify-content: center;
        }
    }
}

</style>
