<template>
<div class="Content-wrapper">
    <div class = "Content-repper"> 
            <div class = "nigger-repper-list">
                <div class= "Content-FirstBlock">
                     <ul>
                        <li>Создадим <span>маркетинговую</span></li>
                        <li><span>стратегию</span> для бизнеса </li>
                        <li>и сделам Вас №1 в своей сфере</li>
                     </ul>
                </div>
            </div>
    <div class = "content-img-text">
        <div class = "content-img-text">
            <div class = "content-img">  
            </div>
            <div class = "content-text">
                <ul>
                    <li>Только современные инструменты</li>
                    <li>привлечения целевых клиентов</li>
                </ul>
            </div>
        </div>
    </div>
    <div class="number-text">
        <div class= "number-text-1">
            <h2>15</h2>
        </div>
    <div class = "img-plus">
    </div>
        <div class="number-text-text-1">
            <ul>
                <li>лет  повышаем</li>
                <li>продажи бизнеса</li>
            </ul>
        </div>
         <div class="number-text-60">
        <div class= "number-text-2">
            <h2>60</h2>
        </div>
    <div class = "img-plus-2">
    </div>
        <div class="number-text-text-2">
            <ul>
                <li>лет  повышаем</li>
                <li>продажи бизнеса</li>
            </ul>
        </div>
    </div>
    </div>
    </div>
    <div class = "Form-Group">
    <div class = "FormFirst">
        <div class= "img-Flag">
    </div>
    </div>
    </div>
</div>
</template>

<style scoped>
.Content-wrapper {
    margin-top: 12vh;
    margin-right: 90vh;
    margin-left: 9vh;
}
.Content-repper {
    display: flex; 
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
span {
    color: #f2bd73;
}
.nigger-repper-list li{
     list-style-type: none;
     color: white;
     font-size: 24px;
}
.content-img-text {
    display: flex; 
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
.content-img {
    background-image: url('../assets/img.png');
    width: 125px;
    height: 125px;
    background:cover;
    background-repeat: no-repeat;
    background-size: 100% ;
    margin-top: -15px;
    margin-left: -50px;
}
.content-text ul{
    color: white;
    font-size: 14px;
    padding-left: 8px;
    list-style-type: none;
    padding-left: 20px;
    margin-top: 30px;
}
.content-img-text {
    display: flex;
    flex-wrap: nowrap;
    justify-items: center;
    justify-content: center;
    align-items: center;
}
.number-text {
    display: flex;  
    flex-direction: row;
    justify-content: center;
    align-items: center;
    }
.number-text h2{
    font-size: 25px;
    background-color: -webkit-linear-gradient( #f7f9fd 8%, #8f8f8f 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: #f7f9fd;
    margin-left: 155px;
    
    margin-top: 60px;
    font-weight: bolder;

}
.img-plus {
    background-image: url('../assets/img-plus.png');
    width: 32px;
    height: 32px;
    background:cover;
    background-repeat: no-repeat;
    background-size: 100% ;
    margin-top: 40px;
    margin-left: 10px;
}
.number-text-text-1 {
    display: flex;  
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
.number-text-text-1 ul{
    color: white;
    font-size: 14px;
    padding-left: 0px;
    list-style-type: none;
    padding-left: 15px;
    margin-top: 50px;
}
.number-text-60{
    display: flex;  
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
.number-text-60 h2{
    font-size: 25px;
    background-color: -webkit-linear-gradient( #f7f9fd 8%, #8f8f8f 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: #f7f9fd;
    margin-left: 75px;
    
    margin-top: 60px;
    font-weight: bolder;
}
.img-plus-2 {
    background-image: url('../assets/img-plus.png');
    width: 32px;
    height: 32px;
    background:cover;
    background-repeat: no-repeat;
    background-size: 100% ;
    margin-top: 40px;
    margin-left: 10px;
}
.number-text-text-2 {
    display: flex;  
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
.number-text-text-2 ul{
    color: white;
    font-size: 14px;
    padding-left: 0px;
    list-style-type: none;
    padding-left: 15px;
    margin-top: 50px;
}
.Form-Group{
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.FormFirst {
    width: 350px;
    height: 500px;
    background-color:#171a1f;
    border: 1px solid black;
}
.img-Flag {
    background-image: url('../assets/flag.png');
    width: 350px;
    height: 500px;
    background-repeat: no-repeat;
    background-color: 100%;

    
}
.Content-Form-Group {
 
    
    margin-right: 60vh;
}
</style>