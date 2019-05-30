# osLearn https://webdemo.myscript.com/


# 1. 信息的表示和处理

  1.1 二进制，八进制，十进制，十六进制的表示与转换
  
  1.2 计算机(内存)的信息存储：二进制存储
  
  1.3 机器码和汇编代码的表示
  
  1.4 内存中程序的表示
  
    1.4.1 4个布尔运算：NOT(~), AND(&), OR(|), EXCLUSIVE-OR(^) 
    
    1.4.2 C 语言中的位级运算, 逻辑运算, 移位运算
      
        1.4.2 位级运算用途： 掩码运算
        1.4.2 逻辑运算： 表达式的结果为 1(true) 或 0(false), 第一个参数求值有结果后，第二个参数将不运算。
        1.4.2 移位运算： 
              左移：补0
              右移：逻辑右移(补0)，算术右移(补最高有效位的值)
              注：java 中， x>>k 为算术右移， x>>>k 为逻辑右移
   1.5 整数表示
   
   1.5.1 无符号数编码：n位二进制, 0(0x00..0) ~ 2^n -1(0xff..f)
    
<svg width="782" height="598" xmlns="http://www.w3.org/2000/svg">
 <!-- Created with Method Draw - http://github.com/duopixel/Method-Draw/ -->
 <g>
  <title>background</title>
  <rect fill="#fff" id="canvas_background" height="600" width="784" y="-1" x="-1"/>
 </g>
 <g>
  <title>Layer 1</title>
  <text stroke="#000" xml:space="preserve" text-anchor="start" font-family="Helvetica, Arial, sans-serif" font-size="24" id="svg_1" y="214.21058" x="113.17516" stroke-width="0" fill="#000000">B2U ( x ) =    x 2</text>
  <path stroke="#000" d="m157.64722,223.65622c0,2.97285 2.95906,2.44893 3.98189,8.91846c0.45742,2.89326 0.58313,3.84347 1.99097,5.94562c1.40779,2.10207 1.99092,2.97285 3.98189,2.97285c1.99097,0 3.98189,0 3.98189,-2.97285c0,-2.97285 0,-14.86408 0,-17.83692c0,-2.97277 0,-5.94562 1.99097,-5.94562c1.99097,0 3.98189,5.94562 5.97286,11.89131c1.99092,5.94562 1.99092,11.89123 1.99092,14.86408c0,2.97277 0,0 0,-11.89131l1.99097,-5.94562l0,-8.91846l0,-2.97285" id="svg_5" fill-opacity="null" stroke-opacity="null" stroke-width="0" fill="none"/>
  <line stroke-linecap="null" stroke-linejoin="null" id="svg_8" y2="196.47078" x2="194.11784" y1="196.47078" x1="181.76489" fill-opacity="null" stroke-opacity="null" stroke="#000" fill="none"/>
  <line stroke-linecap="null" stroke-linejoin="null" id="svg_9" y2="195.88255" x2="194.70608" y1="186.47077" x1="189.41195" fill-opacity="null" stroke-opacity="null" stroke="#000" fill="none"/>
  <line stroke="#000" stroke-linecap="null" stroke-linejoin="null" id="svg_10" y2="198.82373" x2="196.47078" y1="197.64725" x1="192.35313" fill-opacity="null" stroke-opacity="null" fill="none"/>
 </g>
</svg>


   1.5.2 
              
