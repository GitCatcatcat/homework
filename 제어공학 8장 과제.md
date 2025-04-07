### E8.1  
$L(s)=G_c(s)G(s)=\frac{K}{(s+1)^2}$  
$L(s)\vert_{s=jw, K=10}=L(jw)=\frac{10}{(jw+1)^2}=10[\frac{1-w^2}{(w^2+1)^2}+j\frac{-2w}{(w^2+1)^2}]$  
$|L(jw)|=\frac{10}{\sqrt{(w^2+1)^2}}=\frac{10}{w^2+1}$  
$\phi(w)=tan^{-1}(\frac{-2w}{1-w^2})$  

$\therefore $  



$\begin{align}
|L(0)|&=10 , &\phi(0)&=0 \\
|L(0.5)|&=8 , &\phi(0.5)&=-53.13 \\
|L(1)|&=5 , &\phi(1)&=-90 \\
|L(2)|&=2 , &\phi(2)&=53.13 \\
|L(4)|&=0.588 , &\phi(4)&=28.07 \\
|L(\infty)|&=0 , &\phi(\infty)&=0 \\
\end{align}$  


### E8.2  
$G(s)=\frac{5000}{(s+70)(s+500)}$  
$G(jw)=\frac{5000}{(jw+70)(jw+500)}=\frac{5000(35000-w^2-j570w)}{(35000-w^2)^2+(570w)^2}$  
$|G(jw)|=\frac{5000}{\sqrt{(35000-w^2)^2+(570w)^2}}=5000\frac{1}{\sqrt{w^2+70^2}}\frac{1}{\sqrt{w^2+500^2}}$  
$\phi(w)=tan^{-1}(\frac{-570w}{35000-w^2})=tan^{-1}(\frac{-w}{70})+tan^{-1}(\frac{-w}{500})$  

$\therefore $  



$G(j10)=0.141, \; 20logG(j10)=-17.0dB$  
$G(j200)=0.0438, \; 20logG(j200)=-27.2dB$  
$\phi(700)=-139.0^\circ$  


### E8.8  
$T(s)=\frac{100(s-1)}{s^2+25s+100}=\frac{100(s-1)}{(s+5)(s+20)}$  
$T_1(s)=\frac{100(s+1)}{s^2+25s+100}=\frac{100(s+1)}{(s+5)(s+20)}$  

(a)  
$T(jw)=\frac{100(jw-1)}{(jw+5)(jw+20)}$  
pole, zero: $w=1, 5, 20$  
$T_1(jw)=\frac{100(jw+1)}{(jw+5)(jw+20)}$  
pole, zero: $w=1, 5, 20$  

$\therefore $ (i) and (ii) are the same  
$\quad w=1, 5, 20$  

(b)  
at zero: +20dB/dec  
at pole: -20dB/dec  

$w<1$: &emsp; &emsp; &emsp; &nbsp;0dB/dec  
$1<w<5$: &nbsp; +20dB/dec  
$5<w<20$: &emsp; 0dB/dec  
$20<w$: &emsp; &emsp; -20dB/dec  

$\therefore $ (i) and (ii) are the same  
&emsp; at low frequency: &emsp; 0dB/dec  
&emsp; at high frequency: -20dB/dec  

(c)  
$\therefore $  



### E8.12  
$A = \begin{bmatrix}
3 & 1 \\
-1 & 2
\end{bmatrix}$  

$B = \begin{bmatrix}
1 \\
2
\end{bmatrix}$  

$C = [1 -2]$  
$D = 0$  

(a)  
$\therefore T(s) = \frac{-3s+14}{s^2-5s+7}$   

(b)  
$\therefore $  

### P8.1  
(a)  
$L(s)=G_c(s)G(s)=\frac{1}{(1+0.5s)(1+2s)}$  
$\therefore $  

(b)  
$L(s)=G_c(s)G(s)=\frac{3(s^2+1.5s+1)}{(s-2)^2}$  
$\therefore $  

(c)  
$L(s)=G_c(s)G(s)=\frac{s-6}{s^2+5s+6}$  
$\therefore $  

(d)  
$L(s)=G_c(s)G(s)=\frac{10(s+6)}{s(s+1)(s+3)}$  
$\therefore $  


### P8.4  
$G(s) = \frac{2s+2}{s(0.2s+1)(s/30+1)}$  
$H(s)=\frac{100}{s^2+10s+100}$  
$T(s)=\frac{G(s)}{1+G(s)H(s)}$  

$\therefore $  
