<template>
    <header>
        <div class="first-header">
            <div class="container">
                <div class="icons">
                    <div><i class="fas fa-phone"></i> Call us for a Free Quote: 1.800.555.6789</div>
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
                        <a href="#">Home</a>
                        <a href="#">Rates</a>
                        <a href="#">Testimonials</a>
                        <a href="#">FAQ</a>
                        <a href="#">Blog</a>
                        <a href="#">Contact</a>
                        <span class="my_button">Free Quote</span>
                    </nav>
                </div>
            </div>
        </div>
    </header>
</template>
<style scoped lang="scss">
@import '../style/general.scss';
.first-header {
    background-color: #69bf14;
    padding: 10px;
    color: white;
    .icons {
        display: flex;
        justify-content: space-between;
        i {
            margin-right: 7px;
        }
    }
}
.second-header {
    padding: 10px;
    
    .menu {
        display: flex;
        justify-content: space-between;
        nav {
            margin-top: 25px;
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
    }
}
</style>