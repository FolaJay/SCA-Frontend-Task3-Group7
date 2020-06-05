
<template>
    <div class="banner">
        <h2>Intuitive, feature-rich, affordable customer support software </h2>
        <p>Chap fantastic skive off chancer knees up starkers easy peasy up the kyver David, bleeding the BBC tamfactory chimnmey!</p>
        <div class="input">
            <div class="input-group"> 
                <input type="email" v-model="email" placeholder="folasadejay1@gmail.com" class="form-control col-sm-6"/>
                <div class="input-group-btn">
                    <button>Get started</button>
                </div>
            </div>
        </div>
        <div class="image">
            <img src="../assets/banner.png"/>
            <p>Over 130,000 customer agents provide support using Sassland</p>
        </div>   
    </div>
</template>
<style scoped>
.input-group{
    /* border:1px solid rgb(192, 192, 192); */
    max-width: 40%;
    margin:0 auto;
    padding-top:60px;
}
.banner{
    margin-top:100px;
    
}
.banner h2{
    text-align: center;
    max-width: 40%;
    margin:0  auto;
}
.banner p{
    text-align: center;
     max-width: 40%;
    margin:0  auto;
    padding-top:20px;
}
.image{
    text-align: center;
    padding-top:20px;
    
}
.image img{
    width:100%;
    padding-top:20px;
}


</style>