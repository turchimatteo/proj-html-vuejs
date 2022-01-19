<template>
    <footer>
        <div class="first-footer">
            <div class="container">
                <div class="links">
                    <div class="single-link">
                        <h3>About</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus minus nihil quasi esse provident soluta,</p>
                        <img src="../assets/images/avada-movers-logo.png" alt="">
                    </div>
                    <div class="single-link">
                        <h3>Avada movers</h3>
                        <AvadaLinks/>
                    </div>
                    <div class="single-link">
                        <h3>Recent Posts</h3>
                        <PostLink/>
                    </div>
                </div>
            </div>
        </div>
        <div class="second-footer">
            <div class="container">
                <div class="rights">
                    <div>
                        © Copyright 2012-2020 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by Wordpress
                    </div>
                    <div class="icons">
                        <i class="fab fa-facebook-f"></i>
                        <i class="fab fa-twitter"></i>
                        <i class="fab fa-instagram"></i>
                        <i class="fab fa-youtube"></i>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
import AvadaLinks from "./AvadaLinks.vue";
import PostLink from "./PostLink.vue";

export default {
    name: "Footer",
    components: {
        AvadaLinks,
        PostLink,
    },
    props: ['links'],
}
</script>
<style lang="scss" scoped>
@import '../style/general.scss';

footer {
    background-color: #69bf14;
    height: 70vh;
    .first-footer {
        background-color: white;
        height: 50vh;
        position: relative;
        left: 0;
        top: 15px;
        display: flex;
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            .links {
                display: flex;
                justify-content: space-between;
                align-items: center;
                .single-link {
                    width: 20%;
                    display: flex;
                    flex-direction: column;
                    height: 40vh;
                    ul {
                        list-style-type: none;
                        li {
                            margin-top: 15px;
                        }
                        a {
                            list-style-type: none;
                            color: black;
                            text-decoration: none;
                            margin-top: 20px;
                        }
                    }
                    h3 {
                        margin-bottom: 15px;
                        text-transform: uppercase;
                    }
                    p {
                        margin-bottom: 20px;
                        line-height: 1.7;
                    }
                } 
            }
        }
    }
    .second-footer {
        margin-top: 50px;
        color: white;
        .rights {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            .icons {
                margin-top: 10px;
                cursor: pointer;
                i {
                    margin-right: 10px;
                    width: 20px;
                }
            }
        }
    }
}
</style>