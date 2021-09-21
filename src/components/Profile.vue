<template>
  <div class="main">
      <div class="left">
            <div class="logo">
                <img src="../assets/logo1.png"/>
            </div>
            <div class="trophy">
                <img src="../assets/Trophy.png"/>
                <div class="text1"> Leaderboard</div>
            </div>
            <div class="profile">
                <img src="../assets/proF.png"/>
                <div class="text2"> Profile </div>
            </div>
            <div class="setting">
                <img src="../assets/setting.png"/>              
            </div>
            <div class="textS"> Setting </div>
        </div>
        
        <div class="right">
            <div class="login"></div>
            <div class="prof"></div>
        </div>  
    </div>

 
</template>


<style>
    *{
        /* padding:0; */
        margin: 0;
        /* box-sizing: border-box; */
        /* overflow: auto; */
        /* margin-top:0%; */
        /* height: 100%; */
        /* display: block; */
        

        /* width: 100%;
        height: 100%; */
        /* width: 1442px;
        height: 1024px;   */
        /* position: fixed; */
        /* background-size: 1442px*1028px;  */   
    }

    .left{
        /* background-size: 200tpx,1024px; */
        width: 13.87%;
        height: 100%;
        position: relative;
        margin-right: 0%;
        background-color: #40514e;
        outline: #40514e;
        float: left;
        /* background-position: left; */
        /* background-repeat: no-repeat; */
        /* left:0; */
        /* background-position-x: left 0px;
        background-position-y: 0px; */
    }

    .right{
        width: 86.13%;
        height: 100%;
        position: relative;
        margin-left: 0%;
        background-color: #549382;        
        outline: #549382;
        /* float: right; */
        background-position: right;
        /* background-repeat: no-repeat; */
        
    }
    
    .main{
        width: 100%;
        height: 100%;   
        /* position: fixed; */
        /* overflow-y: hidden;   */
        /* overflow: auto; */
        /* overflow:hidden;  */
        /* display: block; */
    }


    .logo{
        /* height 191/1024 wi 191/200 */
        /* top:15/1024 left:4.5/200*/
        height: 18.65%;
        width: 95.5%;
        margin-left: 2.25%;
        margin-right: 2.25%;
        margin-top:1.46%;
    }

    .logo img{        
        height: 100%;
        width: 100%;
        /* position:fixed; */
        /* margin-top: 1.46%;
        padding-left: 0.02%;   */
        /* left: 0.1%;
        top:1.46%; */
        /* float: left; */       
    }

    .trophy{
        /* height 152/1024   w:140/200 
            top:220/1024   left:30/200
        */
        height: 14.84%;
        width: 70%;
        margin-left: 15%;
        margin-right: 15%;
        margin-top: 21.48%;        
    }

    .trophy img{
        /* height 70/152   w:70/140 
            top:237-220/152  left:68-30/140 right:
        */
        height: 46.05%;
        width: 50%;
        margin-top: 11.18%;

        /* margin-left: 20.14%;  
        margin-right: 27.14%;   */
    }
    .text1{
        /* height: 35/152 width 128/140:
        top: 327-307/152 left: 36-30/140*/
        font: SourceHanSansSC-bold;
        color: #FFFFFF;
        height: 23.03%;
        width: 91.43%;
        margin-top: 13.15%;/*problem */
        margin-left: 2.28%;  
        margin-right: 2.28%; 
    }

    .profile{
        /* height: 152/1024 width:143/200: 
        top:  387/1024    left:  28/200 */
        height: 14.84%;
        width: 71.5%;
        margin-left: 14%;
        margin-right: 14%;
        margin-top: 37.79%;   

    }

    .profile img{
        /* height: 73/152 width:97/143: 
        top:  414-387/152    left:  50-28/143 */
        height: 48.03%;
        width: 67.83%;
        /* margin-left: 15.38%;
        margin-right: 15.38%; */
        /* margin-top: 17.76%;    */
    }

    .text2{
        /* height: 35/152 width 128/140:
        top: 327-307/152 left: 36-30/140*/
        font: SourceHanSansSC-bold;
        color: #FFFFFF;
        height: 23.03%;
        width: 91.43%;
        margin-top: 13.15%;/*problem */
        margin-left: 4.28%;  
        margin-right: 4.28%; 
    }


    .setting{
        /* height: 40/1024 width:40/200: 
        top:  962/1024    left:  44/200  right200-66/200*/
        height: 3.9%;
        width: 20%;
        margin-left: 22%;
        margin-right: 67%;
        margin-top: 93.95%;   

    }
    .setting img{
        /* height: 73/152 width:97/143: 
        top:  414-387/152    left:  50-28/143 */
        height: 100%;
        width: 100%;
        /* text-align: left; */
    }

    .textS {
        /* height: 26/1024 width:60/200: 
        top:  967/1024    left:  93/200 */
        font:  SourceHanSansSC-bold;
        color: #FFFFFF;
        height: 2.54%;
        width: 30%;
        margin-left: 46.5%;
        margin-top: 94.43%;      
        float: left;
        
        /* display: block; */
        /* text-align: left; */
        
    }


</style>


