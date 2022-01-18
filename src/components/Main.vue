<template>
    <main>
        <section class="jumbotron">
            <div>
                <h4>Moving without the hassle</h4>
                <h1>We Make it Simple</h1>
                <h4>Professional service with quality and customer satisfaction</h4>
            </div>
        </section>
        <section class="free-quote-online">
            <div><i class="far fa-paper-plane"></i> Get a free quote online now!</div>
        </section>
        <section class="description">
            <div class="container">
                <div class="award-winning">
                    <div>
                        <h4>Headache free</h4>
                        <h2>Award winning moving company</h2>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magnam at repellat, dolorem non iste, sint ut fugiat necessitatibus autem eos laudantium, exercitationem nihil corrupti dolorum quo! Temporibus vero deleniti at.</p>
                        <span class="my_button">Read our testimonials</span>
                    </div>
               </div>
            </div>
        </section>
    </main>
</template>
<style scoped lang="scss">
@import '../style/general.scss';

.jumbotron {
    background-image: url("../assets/images/avada-movers-homeherobackground-final.jpg");
    height: 70vh;
    background-size: cover;
    background-position: center;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    line-height: 1.5;
    text-transform: uppercase;
    font-weight: bold;
    h1 {
        font-size: 50px;
    }
}
.free-quote-online {
    background-color: #1975c0;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 50px;
    font-size: 16px;
    text-transform: uppercase;
}
.description {
    background-color: #e9e9e9;
}
.award-winning {
    height: 50vh;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    line-height: 1.5;
    p {
        margin-bottom: 30px;
    }
}
</style>