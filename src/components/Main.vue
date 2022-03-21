<template>
    <main class="main">
        <section class="home section">
            <div class="home__container container grid">
                <img class="home__img" src="../assets/salad.png" alt="">
                <div class="home__data">
                    <h1 class="home__title">Good Food Us</h1>
                    <h1 class="home__title">Good Mood</h1>
                    <p class="home__description">I would think that conserving our natural resources should be a conservative position: Not to waste food, and not to throw away a lot of the food that we buy</p>
                    <div class="gap">
                    <button type="submit" class="ds">Daftar Sekarang</button>
                    <button type="submit" class="au">About Us</button>
                    </div>
                </div>
            </div>
        </section>
        <section class="category section">
            <h2 class="section__title">Browse Our Category</h2>
            <h2 class="section__receipt">Receipt</h2>
            <div class="card">
                <div class="card__data">
                <img class="card__img" src="../assets/cupcake.png" alt="">
                <div class="card__title">Cupcake</div>
                <p class="card__items">22 Items</p>
                </div>
                <div class="card__data">
                <img class="card__img" src="../assets/pizza 1.png" alt="">
                <div class="card__title">Pizza</div>
                <p class="card__items">25 Items</p>
                </div>
                <div class="card__data">
                <img class="card__img" src="../assets/kebab 1.png" alt="">
                <div class="card__title">Kebab</div>
                <p class="card__items">12 Items</p>
                </div>
                <div class="card__data">
                <img class="card__img" src="../assets/salmon 1.png" alt="">
                <div class="card__title">Salmon</div>
                <p class="card__items">22 Items</p>
                </div>
                <div class="card__data">
                <img class="card__img" src="../assets/doughnut 1.png" alt="">
                <div class="card__title">Doughnut</div>
                <p class="card__items">11 Items</p>
                </div>
            </div>
            <div class="btn-nxt">
                <button class="next">NEXT</button>
                <button class="pre">PREV</button>
                
            </div>
        </section>
        <section class="trending section">
            <h2 class="section__title">Browser Our Trending</h2>
            <h2 class="section__receipt">Receipt</h2>
            <div class="card-t">
                <div class="card-t__data">
                    <img src="../assets/pizza.png" alt="">
                    <div class="card-t__title">Pizza Paperoni</div>
                    <p class="card-t__kind">Pizza</p>
                    
                </div>
                <div class="card-t__data">
                    <img src="../assets/meat.png" alt="">
                    <div class="card-t__title">Pizza Meat</div>
                    <p class="card-t__kind">Pizza</p>
                    
                    
                </div>
                <div class="card-t__data">
                    <img src="../assets/kebab.png" alt="">
                    <div class="card-t__title">Doner Kebab</div>
                    <p class="card-t__kind">Kebab</p>
                    
                </div>
                <div class="card-t__data">
                    <img src="../assets/salmon-roll.png" alt="">
                    <div class="card-t__title">Salmon Roll</div>
                    <p class="card-t__kind">Salmon</p>
                   
                </div>
                <div class="card-t__data">
                    <img src="../assets/choco.png" alt="">
                    <div class="card-t__title">Cupcake Choco</div>
                    <p class="card-t__kind">Cupcake</p>
                    
                </div>
                <div class="card-t__data">
                    <img src="../assets/d.png" alt="">
                    <div class="card-t__title">Doughnut Milk</div>
                    <p class="card-t__kind">Doughnut</p>
                    
                </div>
                <div class="card-t__data">
                    <img src="../assets/d-uni.png" alt="">
                    <div class="card-t__title">Doughnut Unicorn</div>
                    <p class="card-t__kind">Doughnut</p>
                    
                </div>
                <div class="card-t__data">
                    <img src="../assets/kathi.png" alt="">
                    <div class="card-t__title">Kathi Kebab</div>
                    <p class="card-t__kind">Kebab</p>
                    
                </div>
            </div>
            <div class="all" style="text-align: center">
                <button type="button" class="btn">ALL Receipt</button>
            </div>
        </section>
        <section class="footer">
            <div class="l-footer">
                <h1><img src="../assets/elemes.png" alt=""></h1>
                <p>Jl. Prof. DR, Satrio No.7, RT.3/RW.3, Karet Kuningan, Kecamatan Setiabudi, Kota Jakarta Selatan, Daerah Khusus Ibukota Jakarta 12950</p>
                <button class="imail"><img src="../assets/email.png"  style="background: white" alt=""></button>
                <button class="phone"><img src="../assets/phone.png"  style="background: white" alt=""></button>
                <button class="ig"><img src="../assets/ig.png"  style="background: white" alt=""></button>
            </div>
            <ul class="r-footer">
                <li>
                    <h2>Categories</h2>
                    <ul class="box">
                        <li>Cupcake</li>
                        <li>Pizza</li>
                        <li>Kebab</li>
                        <li>Salmon</li>
                    </ul>
                </li>
                <li>
                    <h2>About Us</h2>
                    <ul class="box">
                        <li>About Us</li>
                        <li>Faq</li>
                        <li>Report Problem</li>
                    </ul>
                </li>
                <li>
                    <h2>Newsletter</h2>
                    <ul class="box">
                        <li>Get now free 50% discount for all products on your first order</li>
                        <li>
                            <input class="email" type="text" placeholder="Your email address"><button class="b-email">SEND</button></li>
                        <li><img src="../assets/email.png" alt="email"> elemesid@gmail.com</li>
                        <li><img src="../assets/phone.png" alt="phone"> 0888 1111 2222</li>
                    </ul>
                </li>
            </ul>
        </section>
    </main>
</template>
<script>
export default {
    name: 'Main'
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500;600;700&display=swap');
.imail{
    background: white;
    border: none;
    height: 40px;
    width: 40px;
}
.phone{
    background: white;
    border: none;
    height: 40px;
    width: 40px;
}
.ig{
    background: white;
    border: none;
    height: 40px;
    width: 40px;
}
.phone:hover{
    background: #8BAC3E;
    border-radius: 24px;
}
.ig:hover{
    background: #8BAC3E;
    border-radius: 24px;
}
.imail:hover{
    background: #8BAC3E;
    border-radius: 24px;
}
.star{
    padding-bottom: 12px;
    background: url('../assets/star.png');
    background-repeat: no-repeat;
}
.no-star{
    background: url('../assets/no-star.png');
    background-repeat: no-repeat;
}
.card-t__title{
    font-weight: 600;
    font-size: 26px;
}
.card-t__kind{
    font-weight: 500;
    font-size: 18px;
    color: #8BAC3E;
}
.btn-nxt{
    margin-top: 50px;
}
.card__data:nth-child(2){
    background: #E6F3F5;
}
.card__data:nth-child(3){
    background: #EAEEFA;
}
.card__data:nth-child(4){
    background: #F9EEF3;
}
.card__data:nth-child(5){
    background: #F3F7D9;
}
.pre,.next{
    width: 113px;
    margin-left: 10px;
    height: 50px;
    background: #8BAC3E;
    border-radius: 100px;
    border: none;
    color: white;
    float: right;
}
.email{
    width: 150px;
    height: 40px;
    border: 1px solid #000000;
    box-sizing: border-box;
    border-radius: 8px 0px 0px 8px;
    padding: 10px;
}
.b-email{
    padding: 10px 10px;
    color: white;
    border: none;
    height: 41px;
    background: #8BAC3E;
    border-radius: 0px 8px 8px 0px;
}
.footer{
    display: flex;
    flex-flow: row wrap;
    padding: 50px;
    height: 359px;
    background: #F9FFF7;
}
.l-footer{
    text-align: left;
    margin-right: 1.25rem;
    margin-bottom: 2em;
}
.l-footer p{
    margin-top: 20px;
    text-align: justify;
    font-weight: 400;
}
.footer > * {
    flex: 1 100%;
}
.footer ul{
    list-style: none;
    padding-left: 0;
}
.r-footer{
    text-align: left;
    display: flex;
    flex-flow: row wrap;
}
.r-footer > *{
    flex: 1 50%;
}
.box{
    text-align: left;
}
li{
    line-height: 2rem;
    font-weight: 400;
}
.h-box{
    column-count: 2;
    column-gap: 1.25em;
}
.l-footer p{
    padding-right: 20%;
}
@media screen and (min-width: 600px) {
    .r-footer > *{
        flex: 1;
    }
    .about{
        flex-grow: 2;
    }
    .l-footer{
        flex: 1 0px;
    }
    .r-footer{
        flex: 2 0px;
    }
}
.btn{
    font-size: 16px;
    padding: 10px 20px;
    color: white;
    border: none;
    background-color: #8BAC3E;
    border-radius: 100px;
}
.all{
    margin-top: 100px;
}
.trending, .category{
    text-align:left;
}
.card{
    display: flex;
    padding-top: 1rem;
    flex-direction: row;
    gap: 1.5rem;
}
.card-t{
    display: flex;
    padding-top: 1rem;
    flex-wrap: wrap;
    gap: 1rem;
}
.card-t__data{
    border-radius: 17px;
    background: #E6F3F5;
    display: grid;
    row-gap: 1rem;
    height: 306px;
    padding: 30px 20px;
    width: 287.5px;
}
.card-t__data:nth-child(2){
    background: #E6F3F5;
}
.card-t__data:nth-child(3){
    background: #EAEEFA;
}
.card-t__data:nth-child(4){
    background: #F9EEF3;
}
.card-t__data:nth-child(5){
    background: #F0FEEB;
}
.card-t__data:nth-child(6){
    background: #F3F7D9;
}
.card-t__data:nth-child(7){
    background: #F3F7D9;
}
.card-t__data:nth-child(8){
    background: #EAEEFA;
}
.card-t__data img{
    border-radius: 6px;
}
.card__data:hover{
    background: url("../assets/bg.png");
    height: 229px;
    opacity: 0.7;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}
.card__data{
    background: #F0FEEB;
    display: grid;
    row-gap: 1rem;
    padding: 2rem 1.5rem;
    text-align: center;
    height: 175px;
    width: 230px;
}
.card__data img{
    text-align: center;
}
.card__img{
    height: 47px;
    width: 47px;    
}
main{
    padding: 30px 10%;
}
*{
    font-family: "Rubik", sans-serif;
}
.ds{
    box-shadow: 0px 8px 8px 0px;
    border: none;    
    background: #8BAC3E;
    border-radius: 20px;
    padding: 10px 18px;
    margin-right: 20px;
}
.au{
    cursor: pointer;
    border: none;
    border-radius: 20px;
    background: #F2F2F2;
    padding: 10px 18px;
    font-weight: 500, medium;
}
.home__img{
    order: 1;
}
.section{
    padding: 4.5rem 0 1rem;
}
.section__receipt{
    color: #8BAC3E;
}
.container{
    text-align: left;
    max-width: 968px;
    margin-left: 1.5rem;
    margin-right: 1.5rem;
}
.grid{
    display: grid;
    gap: 1.5rem;
}
.home__container{
    row-gap: 3rem;
    grid-template-columns: repeat(2,1fr);
}
.home__title{
    color: #8BAC3E;
    font-weight: 500;
    font-size: 64px;
}
.home__description{
    margin-top: 2rem;
    margin-bottom: 2rem;
    text-align: justify;
}
.home__data{
    padding: 0 0;
}
@media screen and(max-width: 480px) {
    .home__data{
        display: flex;
    }
}
</style>

