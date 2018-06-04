<template>
    <div id="app">
        <div class="font" data-id="A">
            <div class="a"></div>
        </div>
        <div class="font" data-id="B">
            <div class="b"></div>
        </div>
        <div class="font" data-id="C">
            <div class="c"></div>
        </div>
        <div class="font" data-id="D">
            <div class="d"></div>
        </div>
        <div class="font" data-id="E">
            <div class="e"></div>
        </div>
        <div class="font" data-id="F">
            <div class="f"></div>
        </div>
        <div class="font" data-id="G">
            <div class="g"></div>
        </div>
        <div class="font" data-id="H">
            <div class="h"></div>
        </div>
        <div class="font" data-id="I">
            <div class="i"></div>
        </div>
        <div class="font" data-id="J">
            <div class="j"></div>
        </div>
        <div class="font" data-id="K">
            <div class="k"></div>
        </div>
        <div class="font" data-id="L">
            <div class="l"></div>
        </div>
        <div class="font" data-id="M">
            <div class="m"></div>
        </div>
        <div class="font" data-id="N">
            <div class="n"></div>
        </div>
        <div class="font" data-id="O">
            <div class="o"></div>
        </div>
        <div class="font" data-id="P">
            <div class="p"></div>
        </div>
        <div class="font" data-id="Q">
            <div class="q"></div>
        </div>
        <div class="font" data-id="R">
            <div class="r"></div>
        </div>
        <div class="font" data-id="S">
            <div class="s"></div>
        </div>
        <div class="font" data-id="T">
            <div class="t"></div>
        </div>
        <div class="font" data-id="U">
            <div class="u"></div>
        </div>
        <div class="font" data-id="V">
            <div class="v"></div>
        </div>
        <div class="font" data-id="W">
            <div class="w"></div>
        </div>
        <div class="font" data-id="">
            <div class=""></div>
        </div>
        
    </div>
</template>

<script>
export default {
    name: 'App',
    components: {}
}
</script>

<style scoped lang="scss">
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    width: 100%;
    text-align: center;
    .font{
        width: 200px;
        height: 200px;
        display: inline-block;
        margin: 20px;
        overflow: hidden;
        border: 1px solid #999;
        .u{
            position:relative;
            top: 35px;
            left: 50px;
            width: 60px;
            height: 80px;
            border-width: 0 15px 0 15px;
            border-color: #000;
            border-style: solid;
            &:before{
                position: absolute;
                content: '';
                top: 65px;
                left: -15px;
                width: 60px;
                height: 45px;
                border-width: 0 15px 15px 15px;
                border-color: #000;
                border-style: solid;
                border-radius: 0 0 200% 200% /0 0 300% 300%;
            }
        }

        .t{
            width: 80px;
            height: 15px;
            background: #000;
            position: relative;
            left: 60px;
            top:40px;
            &:after{
                content: '';
                height: 110px;
                width: 15px;
                background: #000;
                position: absolute;
                left: 32.5px;
            }
        }
        .s{
            position: relative;
            left: 50px;
            top:40px;
            transform:rotate(4deg);
            &:after{
                content: '';
                width: 50px;
                height: 60px;
                position:absolute;
                top:63px;
                left:10px;
                border-width:15px 0 13px 15px;
                border-color:#000000;
                border-style:solid;
                border-radius:200% 0 0 200% /100% 0 0 100%;
                transform:rotate(-153deg);
            }
            &:before{
                content: '';
                width: 40px;
                height: 60px;
                position:absolute;
                top:-30px;
                left:-2px;
                border-width:15px 0 13px 15px;
                border-color:#000000;
                border-style:solid;
                border-radius:300% 0 0 300% /200% 0 0 200%;
                transform:rotate(28deg);
            }
        }
        .r{
            position: relative;
            top:30px;
            left: 60px;
            width: 0;
            height: 130px;
            border-left: 15px solid #000;
            &:after{
                content: '';
                position: absolute;
                width: 50px;
                height: 45px;
                border-width: 15px 10px 15px 0;
                border-color: #000;
                border-style: solid;
                border-top-right-radius: 50%;
                border-bottom-right-radius: 50%;
            }
            &:before{
                content: '';
                width: 15px;
                height: 80px;
                position: absolute;
                transform:rotate(-50deg);
                left: 15px;
                top:55px;
                background: #000;
            }  
        }
        .q{
            position:relative;
            top:30px;
            left:45px;
            width:70px;
            height:100px;
            border-width:14px 16px 14px 16px;
            border-color:#000000;
            border-style:solid;
            border-radius:55% /52%;
            &:after{
                content: '';
                width: 20px;
                height: 60px;
                position:absolute;
                content:'';
                top:80px;
                left:55px;
                border-width:16px 0 13px 13px;
                border-color:#000000;
                border-style:solid;
                border-radius:300% 0 0 300% /150% 0 0 150%;
                transform:rotate(-85deg);
            }
            &:before{
                content: '';
                width: 60px;
                height: 30px;
                background: #fff;
                z-index: 1;
                position: absolute;
                left: 80px;
                top:110px;
                transform:rotate(-10deg);
            }
        }
        .p{
            position: relative;
            top:30px;
            left: 60px;
            width: 0;
            height: 130px;
            border-left: 15px solid #000;
            &:after{
                content: '';
                position: absolute;
                width: 50px;
                height: 45px;
                border-width: 15px 10px 15px 0;
                border-color: #000;
                border-style: solid;
                border-top-right-radius: 50%;
                border-bottom-right-radius: 50%;
            }   
        }
        .o{
            position:relative;
            top:30px;
            left:45px;
            width:70px;
            height:100px;
            border-width:14px 16px 14px 16px;
            border-color:#000000;
            border-style:solid;
            border-radius:55% /52%;
        }
        .n{
            position: relative;
            top:30px;
            left:50px;
            width:65px;
            height:125px;
            border-width:0 15px 0 15px;
            border-color:#000;
            border-style:solid;
            &:after{
                transform:skew(30deg,0);
                position:absolute;
                content:'';
                top:0;
                left:25px;
                width:16px;
                height:125px;
                background-color:#000;   
            }
        }
        .m{
            position: relative;
            top:20px;
            left:40px;
            width:80px;
            height:125px;
            border-width:0 15px 0 15px;
            border-color:#000;
            border-style:solid;
            &:after{
                transform:skew(20deg,0);
                position:absolute;
                content:'';
                top:0;
                left:14px;
                width:12px;
                height:110px;
                background-color:#000;
            }
            &:before{
                transform:skew(-20deg,0);
                position:absolute;
                content:'';
                top:0;
                right:14px;
                width:12px;
                height:110px;
                background-color:#000;
            }
        }
        .l{
            width: 60px;
            height: 100px;
            position: relative;
            border-width: 0 0 15px 15px;
            border-style: solid;
            border-color: #000;
            left: 60px;
            top:35px;
        }
        .k{
            width: 0px;
            height: 125px;
            position: relative;
            border-left: 15px solid #000;
            left: 60px;
            top:30px;
            &:after{
                width: 15px;
                height: 70px;
                content: '';
                position: absolute;
                background: #000;
                left: 10px;
                top:0;
                transform: rotate(45deg);
            }
            &:before{
                width: 15px;
                height: 80px;
                content: '';
                position: absolute;
                background: #000;
                left: 18px;
                top:40px;
                transform: rotate(-45deg);
            }
        }
        .j{
            width: 50px;
            height: 80px;
            border-width:0 15px 15px 14px;
            border-color:#000000;
            border-style:solid;
            border-radius:0 0 75%75%;
            position: relative;
            left: 50px;
            top:70px;
            &:after{
                content: '';
                position: absolute;
                width: 30px;
                height: 30px;
                right: -15px;
                top:-40px;
                border-width: 15px 15px 0 0;
                border-color:#000000;
                border-style:solid;
            }
            &:before{
                content: '';
                position: absolute;
                left: -35px;
                top:-10px;
                width: 50px;
                height: 80px;
                background: #fff;
                transform:rotate(-30deg);
            }
        }
        .i{
            width: 60px;
            height: 120px;
            border-width: 15px 0 15px 0;
            border-style: solid;
            border-color: #000;
            position: relative;
            left: 65px;
            top: 25px;
            &:after{
                content: '';
                width: 15px;
                height: 120px;
                background-color: #000;
                position: absolute;
                top:0px;
                left: 22.5px;
            }
        }
        .h{
            width: 55px;
            height: 120px;
            border-width: 0 15px 0 15px;
            border-style: solid;
            border-color: #000;
            position: relative;
            left: 55px;
            top: 35px;
            &:after{
                content: '';
                width: 60px;
                height: 13px;
                background-color: #000;
                position: absolute;
                top:50px;
                left: 0;
            }
        }
        .g{
            width: 80px;
            height: 90px;
            border: 15px solid #000;
            border-radius: 50%;
            position: relative;
            left: 50px;
            top: 40px;
            &:after{
                content: '';
                width: 65px;
                height: 65px;
                background: #fff;
                position: absolute;
                right: -30px;
                top:12px;
                transform:rotate(45deg);
                z-index: 1;
            }
            &:before{
                z-index: 2;
                position: absolute;
                right: 0;
                top:60px;
                content: '';
                width: 30px;
                height: 30px;
                border-width: 15px 15px 0 0;
                border-style: solid;
                border-color: #000;
            }
        }
        .f{
            width: 60px;
            height: 110px;
            border-width: 15px 0 0 17px;
            border-style: solid;
            border-color: #000;
            position: relative;
            left: 55px;
            top: 30px;
            &:after{
                content: '';
                width: 60px;
                height: 15px;
                background-color: #000;
                position: absolute;
                top:40px;
                left: 0;
            }
        }
        .e{
            width: 60px;
            height: 100px;
            border-width: 15px 0 15px 17px;
            border-style: solid;
            border-color: #000;
            position: relative;
            left: 55px;
            top: 30px;
            &:after{
                content: '';
                width: 60px;
                height: 15px;
                background-color: #000;
                position: absolute;
                top:40px;
                left: 0;
            }
        }
        .d{
            position: relative;
            top:50px;
            left: 60px;
            width: 0;
            height: 95px;
            border-left: 15px solid #000;
            &:after{
                content: '';
                position: absolute;
                width: 50px;
                height: 65px;
                border-width: 15px 10px 15px 0;
                border-color: #000;
                border-style: solid;
                border-top-right-radius: 50%;
                border-bottom-right-radius: 50%;
            }
        }
        .c{
            width: 80px;
            height: 90px;
            border: 15px solid #000;
            border-radius: 50%;
            position: relative;
            left: 50px;
            top: 40px;
            &:after{
                content: '';
                width: 65px;
                height: 65px;
                background: #fff;
                position: absolute;
                right: -30px;
                top:12px;
                transform:rotate(45deg);
            }
        }
        .b{
            position: relative;
            top:30px;
            left: 50px;
            width: 0;
            height: 140px;
            border-left: 15px solid #000;
            &:after{
                content: '';
                position: absolute;
                width: 50px;
                height: 45px;
                border-width: 15px 10px 15px 0;
                border-color: #000;
                border-style: solid;
                border-top-right-radius: 50%;
                border-bottom-right-radius: 50%;
            }
            &:before{
                content: '';
                position: absolute;
                bottom: 0;
                width: 50px;
                height: 45px;
                border-width: 15px 10px 15px 0;
                border-color: #000;
                border-style: solid;
                border-top-right-radius: 50%;
                border-bottom-right-radius: 50%;
            }
        }
        .a{
            width: 60px;
            height: 100px;
            border-bottom: 15px solid #000;
            position: relative;
            left: 70px;
            top: -10px;
            &:after{
                content: '';
                width: 15px;
                height: 130px;
                position: absolute;
                left: -4px;
                top:40px;
                background-color: #000;
                transform:skew(-22deg);
            }
            &:before{
                content: '';
                width: 15px;
                height: 130px;
                position: absolute;
                right: -4px;
                top:40px;
                background-color: #000;
                transform:skew(22deg);
            }
        }
    }
}
</style>
