<template>
    <div class="head">
        
            <div class="send">
                <p>水网密度指数= (Anix河 流长度/区域面积十Aax水域面积(湖泊、水库、河渠和近海)<br>
                    区域面积+Arex水资源量“区域面积)13
                </p>
                <p>式中： Ariv————河流长度的归一化系数，参考值为84.3704083981;</p>
                         <span class="send-one">  Alak—————水域面积的归一化系数，参考值为591.7908642005;</span>
                         <br>
                         <span class="send-one">   Ares————水资源量的归一化系数，参考值为86.3869548281。</span>
                
            </div>
         <div class="xuxian"></div>
         <div class="btn-div">
                 <h2 class="btn-h">指标生态意义：</h2>
               <p>水网密度指数被评价区域内河流总长度、水域面积和水资源量占被评价区域面积的比重。用于反映被评价区域水的丰富程度。</p>
           
        </div>
        </div>
   
</template>


<style scoped>
 
p{
    text-indent: 2em; 
}
.head{
    width: 60%;
    height: 500px;
     margin: 60px 80px 60px 340px;
}
.send{
    width:60%;
}
.send {
    font-size: 16px;
}
.send-one{
    position: relative;
    left: 86px;
    font-size: 16px;
}
.xuxian{
    border-top: 1px dashed #707070;
    margin-top:46px ;
    height: 1px;
    width: 96%;
    margin-left:-40px ;
    
}
.btn-h{
    color: #333333;
    font-size: 20px;
    margin: 24px 2px 20px 2px;
}
.btn-div p{
    color: #333333;
    font-size: 16px;
}
</style>