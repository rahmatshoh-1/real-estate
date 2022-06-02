<template>
    <div class="card border cursor-pointer">
        <div class="card__img">
            <img src="../static/img2.jpg" alt="">
        </div>
        <div class="px-8 pt-4">
            <h3 class="font-bold">
                Studio apartment,<br>
                28 m2, 5/10 Fl
            </h3>
            <div>
                <span class="font-bold dollarPrice1">$17,400</span>
                <span class="dollarPrice2">/ $1600 per m2</span>
            </div>
            <div>
                <span class="euroPrice1">€11,878</span>
                <span class="euroPrice2">/ €1589 per m2</span>
            </div>
            <p class="py-4">
                Pomurska, Apače
            </p>
        </div>
        <img src="../static/bg_hover.png" class="card__bg_hover -mt-64" alt="">

    </div>
    
</template>
<style scoped>
.card{
    width: 283px;
    border-radius: 25px;
    background: #FCFBFA;
    font-family: 'Comfortaa', cursive;
    margin-bottom: 30px;
}
.card h3{
    font-size: 20px;
}
.card__img{
    height: 190px;
}
.card__img img{
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
}
.dollarPrice1{
    font-size:20px;
    color: #61A4DA;
}
.dollarPrice2,
.euroPrice2,
.euroPrice1
{
    font-size: 11px;
}
.euroPrice1{
    font-weight: bold;
    color: #61A4DA;
}
.card__bg_hover{
    position: absolute;
    z-index: -1;
    display: none;
    margin-left: -50px;
}
.card:hover .card__bg_hover{
    display: block;
    transition: all 0.3s ease;
}
</style>