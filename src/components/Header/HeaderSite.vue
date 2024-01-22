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
            <div class="header_SecondBlock_logo">
               <RouterLink to="/"><img src="../../assets/headerLogo/redi_logo.jpg" alt=""></RouterLink>
            </div>
            <div class="header_SecondBlock_Search">
                <input type="search" placeholder="Пошук товару...">
            </div>
            <div class="header_SecondBlock_Operator">
                <div class="header_SecondBlock_Operator_logo">
                    <img src="../../assets/headerLogo/call.png" alt="">
                </div>
                <div class="header_SecondBlock_Operator_content">
                    <div class="header_SecondBlock_Operator_content_title">
                        <span>
                            Консультація
                        </span>
                    </div>
                    <div class="header_SecondBlock_Operator_content_number">
                        <span>+38(050)341-29-01</span>
                    </div>
                </div>
            </div>
            <div class="header_SecondBlock_basket">
                <div class="header_SecondBlock_basket_logo">
                    <RouterLink to="/"><img src="../../assets/headerLogo/pack.png" alt=""></RouterLink>
                </div>
            </div>
        </div>
        <div class="header_ThirdBlock">
            <div class="header_ThirdBlock_nav">
                <ul class="nav">
                    <li>
                        <div class="nav_element">
                            <RouterLink to=""><span>Iphone 14 </span></RouterLink>
                            <div class="nav_element_dropdown">
                                <ul>
                                    <li>
                                        <RouterLink to="">14 Pro Max</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">14 Pro</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">14</RouterLink>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="nav_element">
                            <RouterLink to=""><span>Iphone 13 </span></RouterLink>
                            <div class="nav_element_dropdown">
                                <ul>
                                    <li>
                                        <RouterLink to="">13 Pro Max</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">13 Pro</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">13</RouterLink>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="nav_element">
                            <RouterLink to=""><span>Iphone 12 </span></RouterLink>
                            <div class="nav_element_dropdown">
                                <ul>
                                    <li>
                                        <RouterLink to="">12 Pro Max</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">12 Pro</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">12</RouterLink>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="nav_element">
                            <RouterLink to=""><span>Iphone 11 </span></RouterLink>
                            <div class="nav_element_dropdown">
                                <ul>
                                    <li>
                                        <RouterLink to="">11 Pro Max</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">11 Pro</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">11</RouterLink>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="nav_element">
                            <RouterLink to=""><span>Iphone X </span></RouterLink>
                            <div class="nav_element_dropdown">
                                <ul>
                                    <li>
                                        <RouterLink to="">XS Max</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">XS</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">XR</RouterLink>
                                    </li>
                                    <li>
                                        <RouterLink to="">X</RouterLink>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </div>
    <RouterView/>
</template>


<script>











</script>


<style>
@import url('../../view/Header.css');
</style>