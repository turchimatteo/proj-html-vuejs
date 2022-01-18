<template>
    <section>
        <div class="container">
            <div class="free-quote">
                    <div>
                        <h2>Request A Free Quote</h2>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magnam at repellat, dolorem non iste, sint ut fugiat necessitatibus autem eos laudantium, exercitationem nihil corrupti dolorum quo! Temporibus vero deleniti at.</p>
                        <span class="my_button">Click here</span>
                    </div>
               </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
@import '../style/general.scss';

section {
    background-image: url("../assets/images/avada-movers-request-quote-background.jpg");
    height: 65vh;
    background-size: cover;
    background-position: top;
    background-repeat: no-repeat;
    margin-top: 20px;
    display: flex;
    .container {
        display: flex;
        justify-content: center;
        align-items: center;
        .free-quote {
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            line-height: 1.8;
            width: 60%;
            p {
                margin-bottom: 30px;
                color: #6b6b6b;
                text-align: center;
            }
        
        }
    }
}
</style>