<template>
    <div class='main'>
        <section id='intro'>
            <p class="mainText">명예옷장 </p><p class="mainText" id="subMainText">은,</p>
            <br><br><br>
            <p>지식과 경험을 바탕으로 후학을 양성하는 스승이</p>
            <br>
            <p>추억과 이야기가 담겨 있어 절대 버릴 수 없었던 좋은 옷을 기부하고,</p>
            <br><br>
            <p>밝은 미래를 꿈꾸며 열심히 노력하는 제자가</p>
            <br>
            <p>좋은 옷을 저렴하게 구입할 뿐만 아니라 의미 있는 이야기를 함께 구매 함으로써,</p>
            <br><br>
            <p>스승과 제자간의 명예로운 가치를 나누는 사외적 협동 프로젝트입니다.</p>
            <img src="../assets/planModel.png">
        </section>
        <section id="mean">
            <p class="subText">묵혀둔 자원의 활용,</p>
            <p>잘 사용하였지만, 지금은 필요 없는 잉여 물품을 묵혀두지 말고 필요한 사람에게 제공</p>
            <p class="subText">스승과 제자의 교류</p>
            <p>지식뿐만 아니라 마음을 헤아려 가치를 나눌 수 있는 훈훈한 기회</p>
            <p class="subText">의미의 시대,</p>
            <p>유형의 교류를 통해 무형의 가치를 함께 하는 의미의 시대를 공감</p>
            <br>
        </section>
    </div>
    
</template>

<script>
export default {
    
}
</script>

<style scoped>
    @font-face{
        font-family: 'Nanum Myeongjo';
        src: url(//fonts.googleapis.com/earlyaccess/nanummyeongjo.css);
    }
    
    .mainText{
        font-family: 'Nanum Myeongjo';
        font: bold;
        display: inline;
        color: rgb(202, 143, 10);
    }
    #subMainText{
        color: rgb(105,105,105);
    }
    .subText{
        font-family: 'Nanum Myeongjo';
        font-weight: bold;
    }

    #intro{
        text-align: center;
        padding-top: 10vw;
    }
    @media(max-width:600px){
        .main{
            margin-right: 10px;
            margin-left: 10px;
        }
        .mainText{
            font-size: 9vw;
        }
        #subMainText{
            font-size: 8vw;
        }
        img{
            width: 80vw;
            height: 30vw;
        }
        #mean{
            text-align: left;
            padding-bottom: 10vw;
        }
        .subText{
            padding-bottom: 3vw;
            padding-top: 8vw;
        }
    }
    @media(min-width:601px){
        .main{
            width: 100vw;
            margin: auto;
            text-align: center;
        }
        .mainText{
            font-size: 3vw;
        }
        #subMainText{
            font-size: 2.62vw;
        }
        .subText{
            font-size: 2.65vw;
            padding-bottom: 5vw;
            padding-top: 10vw;
        }
        img{
            width: 40vw;
            height: 17vw;
        }
        p{
            font-size: 1.5vw;
        }

        section{
            text-align: left;
        }

        .main{
            min-height: 100vh;
            height: calc(100vh-89px);
            background-color: rgb(233, 236, 241);
        }

        #mean{
            padding-bottom: 145px;
            margin-left: 20%;
            margin-right: 20%;
        }
    }
</style>