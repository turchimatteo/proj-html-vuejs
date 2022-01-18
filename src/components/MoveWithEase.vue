<template>
    <section class="move-with-ease">
        <div class="container">
            <div class="content">
                <div class="box">
                    <h4>We remove the headache from moving</h4>
                    <h2>Move Whit Ease</h2>
                    <hr>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsa nihil numquam, voluptate commodi culpa blanditiis. Eveniet placeat, explicabo alias iusto molestiae dolorum animi atque.</p>
                    <span class="my_button">Get a free quote now</span>
                </div>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
@import '../style/general.scss';

.move-with-ease {
    background-image: url("../assets/images/avada-movers-movewithease-background-new.jpg");
    height: 80vh;
    background-size: cover;
    background-position: top;
    background-repeat: no-repeat;
    margin-top: 40px;
    display: flex;
    .content {
        display: flex;
        align-items: flex-end;
        justify-content: center;
        flex-direction: column;
        .box {
            background-color: #6bbb14;
            padding: 40px;
            width: 40%;
            line-height: 1.5;
            border: 8px solid #4c8d53;
            text-align: center;
            h4 {
                text-transform: uppercase;
                color: #6b6b6b;
                font-size: 14px;
                margin-bottom: 10px;
            }
            h2 {
                color: white;
                font-size: 35px;
                margin-bottom: 10px;
            }
            hr {
                background-color: #74d315;
                height: 2px;
                border: none;
                width: 70%;
                display: inline-block;
                margin-bottom: 10px;
            }
            p {
                color: white;
                line-height: 1.7;
                margin-bottom: 20px;
            }
        }
    }
}
</style>