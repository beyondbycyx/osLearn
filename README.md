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
    
<math xmlns='http://www.w3.org/1998/Math/MathML'> <mi> B </mi> <mn> 2 </mn> <msub> <mrow> <mi> U </mi> </mrow> <mrow> <mi> w </mi> </mrow> </msub> <mfenced> <mrow> <mover> <mrow> <mi> x </mi> </mrow> <mrow> <mo> &#x2192; <!-- rightwards arrow --> </mo> </mrow> </mover> </mrow> </mfenced> <mo> - </mo> <munderover> <mrow> <mo> &#x2211; <!-- n-ary summation --> </mo> </mrow> <mrow> <mover> <mrow> <mi> i </mi> <mo> = </mo> <mn> 0 </mn> </mrow> <mrow> <mo> - </mo> </mrow> </mover> </mrow> <mrow> <mi> w </mi> <mo> - </mo> <mn> 1 </mn> </mrow> </munderover> <msub> <mrow> <mi> x </mi> </mrow> <mrow> <mi> i </mi> </mrow> </msub> <msup> <mrow> <mn> 2 </mn> </mrow> <mrow> <mi> i </mi> </mrow> </msup> </math>


   1.5.2 
              
