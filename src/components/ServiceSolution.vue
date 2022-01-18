<template>
    <section class="container">
        <div class="service-solution">
            <div class="title">
                <h4>We are professional</h4>
                <h2>Full-Service Solution</h2>
            </div>
            <div class="cards">
                <div class="card">
                    <img src="../assets/images/avada-movers-serviceonephoto-final-600x383.jpg" alt="">
                    <div>
                        <h4>Two Mans Team</h4>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum hic magnam nobis voluptate consequuntur iusto ducimus quis quidem aliquid? Ipsum minus delectus porro ipsam quaerat doloribus tenetur nostrum eius nihil.</p>
                        <span class="my_button">Read Me</span>
                    </div>
                </div>
                <div class="card">
                    <img src="../assets/images/avada-movers-servicetwophoto-final-600x383.jpg" alt="">
                    <div>
                        <h4>We Do All The Lifting</h4>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa quibusdam minus eveniet ut dicta, consectetur vero exercitationem veniam! Voluptates nisi eius rerum tempora quae aperiam quaerat tenetur, esse neque numquam!</p>
                        <span class="my_button">Read Me</span>
                    </div>
                </div>
                <div class="card">
                    <img src="../assets/images/avada-movers-servicethreephoto-final-600x383.jpg" alt="">
                    <div>
                        <h4>Coast To Coast</h4>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente, aspernatur. Nihil neque aperiam, et, numquam exercitationem minus facere ipsam pariatur amet nulla, enim reprehenderit velit facilis blanditiis, Culpa!</p>
                        <span class="my_button">Read Me</span>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped lang="scss">
@import '../style/general.scss';
.service-solution {
    margin-top: 50px;
    .title {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column; 
    h4 {
        text-transform: uppercase;
        color: #6b6b6b;
        font-size: 15px;
    }
    h2 {
        color: #69bf14;
        margin-top: 10px;
        margin-bottom: 20px;
        font-size: 40px;
    }
 }
    .cards {
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-direction: row;
    margin-top: 20px;
    .card {
        border: 6px solid #e9e9e9;
        width: 30%;
        text-align: center;
        font-size: 14px;
        line-height: 1.5;
        padding: 20px;
        img {
            border-bottom: 6px solid #e9e9e9;
            width: 100%;
        }
        h4 {
            color: #1975c0;
            font-size: 20px;
        }
        p {
            margin-bottom: 20px;
            margin-top: 10px;
        } 
        .my_button {
            margin-bottom: 20px;
        }
    }
 }
}
</style>