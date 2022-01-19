<template>
    <header>
        <div class="first-header">
            <div class="container">
                <div class="icons">
                    <div><i class="fas fa-phone"></i> Call us for a Free Quote: <span class="telephone-number">1.800.555.6789</span></div>
                    <div>
                        <i class="fab fa-facebook-f"></i>
                        <i class="fab fa-twitter"></i>
                        <i class="fab fa-instagram"></i>
                        <i class="fab fa-youtube">
                    </i></div>
                </div>
                
            </div>
        </div>
        <div class="second-header">
            <div class="container">
                <div class="menu">
                    <div class="logo">
                        <img src="../assets/images/avada-movers-logo.png" alt="">
                    </div>
                    <nav>
                        <ul>
                            <li v-for="(link, index) in links" :key="index" :class="{current: link.current}">
                                <a href="link.url"> {{ link.text }}</a>
                            </li>
                        </ul>
                        <span class="my_button">Free Quote</span>
                    </nav>
                </div>
            </div>
        </div>
    </header>
</template>
<script>
export default {
    name: "Header",
    props: ['links'],
    data: function() {
        return {

        };
    }
}
</script>
<style scoped lang="scss">
@import '../style/general.scss';
.first-header {
    background-color: #69bf14;
    padding: 10px;
    color: white;
    .icons {
        display: flex;
        justify-content: space-between;
        .telephone-number {
            cursor: copy;
        }
        i {
            margin-right: 7px;
            cursor: pointer;
        }
    }
}
.second-header {
    padding: 10px;
    background-color: rgba(255, 255, 255, 0.6);
    .menu {
        display: flex;
        justify-content: space-between;
        nav {
            margin-top: 25px;
            display: flex;
            justify-content: center;
            ul {
                display: flex;
                flex-direction: row;
                list-style-type: none;
                a {
                    text-decoration: none;
                    color: black;
                    margin-left: 15px;
                    font-weight: bold;
                }
                a:hover {
                    color: #69bf14;
                }
            }
            .my_button {
                margin-top: -10px;
                height: 43px;
            }
        }
    }
}
</style>