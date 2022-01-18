<template>
    <section>
        <div class="container">
            <div class="testimonials">
                <div class="title">
                    <h4>Happy costumer</h4>
                    <h2>Testimonials</h2>
                </div>
                <div class="all-testimonials">
                    <div class="single-testimonial">
                        <img src="../assets/images/avada-movers-johndoe-final-200x200.jpg" alt="">
                        <h3>John Doe</h3>
                        <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eaque adipisci nostrum porro. Dolor optio quae laboriosam magnam fugit, quod incidunt velit dignissimos quasi maxime veniam, voluptates corporis id quo repudiandae."</p>
                    </div>
                    <div class="single-testimonial">
                        <img src="../assets/images/avada-movers-janedoe-final-200x200.jpg" alt="">
                        <h3>Jane Doe</h3>
                        <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eaque adipisci nostrum porro. Dolor optio quae laboriosam magnam fugit, quod incidunt velit dignissimos quasi maxime veniam, voluptates corporis id quo repudiandae."</p>
                    </div>
                    <div class="single-testimonial">
                        <img src="../assets/images/avada-movers-johnsmith-final-200x200.jpg" alt="">
                        <h3>John Smith</h3>
                        <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eaque adipisci nostrum porro. Dolor optio quae laboriosam magnam fugit, quod incidunt velit dignissimos quasi maxime veniam, voluptates corporis id quo repudiandae."</p>
                    </div>
                </div>
                <span class="my_button">Read more testimonials</span>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
@import '../style/general.scss';

section {
    background-image: url("../assets/images/avada-movers-testimonial-background.jpg");
    height: 100vh;
    background-size: cover;
    background-position: top;
    background-repeat: no-repeat;
    margin-top: 20px;
    display: flex;
    .testimonials {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        .title {
            margin-bottom: 20px;
            margin-top: 30px;
            text-align: center;
        }
        .all-testimonials {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-direction: row;
            text-align: center;
            font-size: 16px;
            line-height: 1.5;
            .single-testimonial {
                padding: 25px;
                margin-bottom: 30px;
                img {
                    border-radius: 50%;
                    width: 50%;
                    margin-bottom: 20px;
                }
                p {
                    color: #6b6b6b;
                    font-style: italic;
                }
                h3 {
                    color: #1975c0;
                    font-size: 22px;
                    margin-bottom: 10px;
                }
            }
        }
    }
}
</style>