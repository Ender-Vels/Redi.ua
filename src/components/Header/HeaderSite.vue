<template>
    <div class="header">
        <div class="header_FirstBlock">
            <div class="header_FirstBlock_nav">
            <ul>
                <li><RouterLink to="/">Головна</RouterLink></li>
                <li><RouterLink to="/">Доставка та оплата</RouterLink></li>
                <li><RouterLink to="/">Обмін та повернення</RouterLink></li>
                <li><RouterLink to="/">Новини</RouterLink></li>
                <li><RouterLink to="/">Контакти</RouterLink></li>
                <li><RouterLink to="/">Про нас</RouterLink></li>
            </ul>
        </div>
        <div class="header_FirstBlock_autorize">
            <div class="header_FirstBlock_autorize_favorite">
                
                <RouterLink to=""><img src="../.././assets/headerLogo/Like.png">Обране</RouterLink>
            </div>
            <div class="header_FirstBlock_autorize_logining">
                
                <RouterLink to=""><img src="../.././assets/headerLogo/Autorize.png">Авторизуватись</RouterLink>
            </div>
        </div>
        </div>
        <div class="header_SecondBlock">

        </div>
    </div>
    <RouterView/>
</template>


<script>






</script>


<style>
.header{
    display: block;
    background-color: rgb(224, 8, 8);
}
.header_FirstBlock{
    display: flex;
    justify-content: space-between;
}

.header_FirstBlock_nav li{
    display: inline-flex;
    padding: 15px;
}
.header_FirstBlock_nav a{
    text-decoration: none;
    font-size: 20px;
    color:white;
}
.header_FirstBlock_nav li:hover{
    background-color: brown;
}
.header_FirstBlock_autorize{
    display: flex;
    padding: 15px;
}
.header_FirstBlock_autorize img{
height: 20px;
}

.header_FirstBlock_autorize a{
   color: white;
   font-size: 20px;
   text-decoration: none;
   margin: 5px;

}
.header_FirstBlock_autorize :hover{
    background-color: brown;
}

</style>