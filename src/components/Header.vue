<template>
<div class= "Heder-SubHeder">
<div class = "Header">
    <div class = "nigger-rob-list">
        <ul>
            <li><span>П</span>родвижение </li>
            <li><span>Р</span>азработка сайтов </li>
            <li><span>В</span>едение социальных сетей </li>
        </ul>
    </div>
    <div class = "Icon-Contacts">
        <div class = "IconHeaderText">
            <div class = "icon">  
            </div>
            <div class = "HeaderText">
                <h1>Казахстан</h1>
            </div>
        </div>
        <div class = "SubHeaderText">
            <p>г. Алматы, улица Центральная №1</p>
        </div>
    </div>
    <div class = "IconContacts0">
        <div class = "IconHeaderText0">
            <div class = "icon0">  
            </div>
            <div class = "HeaderText0">
                <h1>+7 (777) 123-45-67</h1>
            </div>
        </div>

        <div class = "SubHeaderText0">
            <p>mail@gmail.com</p>
        </div>
    </div>
    <div class = "btn-returncall">
        <button>Перезвонить мне</button>
    </div>
</div>
<hr>
  <div class = "menu">
        <ul>
            <li> <a class="AboutUs" href="#">О нас</a> </li>
            <li><a class="AboutUs" href="#">Портфолио</a></li>
            <li><a class="AboutUs" href="#">Клиенты</a></li>
            <li><a class="AboutUs" href="#">Новости</a></li>
            <li><a class="AboutUs" href="#">Контакты</a></li>
            
        </ul>
    </div>
  </div>  
</template>

<style>

.Heder-SubHeder {
    margin-right: 9vh;
    margin-left: 9vh;
}
.Header {
    display: flex; 
    flex-direction: row;
    justify-content: center;
    align-items: center;
}

span {
    color: #f2bd73;
}
.nigger-rob-list li{
     list-style-type: none;
     color: white;
}

.IconContacts {
    margin-left: 100px;

}
.IconHeaderText .icon{
    background-image: url('../assets/icon.png');
    width: 15px;
    height: 23px;
    background:cover;
    background-repeat: no-repeat;
    background-size: 100% ;
    margin-top: 12px;
}
.HeaderText h1{
    color: white;
    font-size: 16px;
    padding-left: 8px;
    margin-right: -65px;  
}
.SubHeaderText p{
    color: #b4b4b4;
    font-size: 13px;
    margin: 0px;
    margin-left: 74px;
    margin-right: -65px;
}
.IconHeaderText {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    width: 238px;
    min-width: 238px;
    max-width: 238px;
}
.IconContacts0 {
    margin-left: 100px;
}
.IconContacts0 .icon0 {
    background-image: url('../assets/icon0.png');
    width: 20px;
    height: 28px;
    background:cover;
    background-repeat: no-repeat;
    background-size: 100% ;
    margin-top: 12px;
}
.HeaderText0 h1{
    color: white;
    font-size: 16px;
    padding-left: 8px;
}
.SubHeaderText0 p{
    color: #b4b4b4;
    font-size: 13px;
    margin: 0px;
    margin-left: 9px;
}
.IconHeaderText0 {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    width: 238px;
    min-width: 238px;
    max-width: 238px;
}
.SubHeaderText0 {
    display: flex;
    justify-content: flex-end;
}
.btn-returncall {
    margin-left: 20px;
}
.btn-returncall button {
    text-align: center;
    border: 2px solid #2f3137;
    border-radius: 4px;
    background: rgb(20,23,28);
    background: linear-gradient(90deg, rgba(20,23,28,1) 35%, rgba(41,44,50,1) 100%);
    color: #6e7073;
    padding: 15px ;
}
.menu {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center!important;
    list-style-position: inside;
    color: white;
    margin-top: 3vh;
    margin-right: 47vh;
}
.menu ul li {
    margin-right: 45px;
}
.menu ul {
    display: flex;
    flex-wrap: nowrap;
    justify-items: center;
    justify-content: center;
    align-items: center;
    list-style-type: none;
    padding-left: 0;
    margin: 0;
}
.menu ul li a{
    color: white;
    text-decoration: none;
    display: inline-block;
}
</style>