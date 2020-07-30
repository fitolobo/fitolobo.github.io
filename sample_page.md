## Ejercicios Interesantes

**En esta sección encontrarás:** Ejercícios que he encontrado en la red que consideré interensates. La mayoría de olimpíadas.  

### 1. April Fools day. Ñoy dungu tüfachi ramtun?

Tricky equal sign.

<img src="https://render.githubusercontent.com/render/math?math=%5CLARGE%20e%20-%20%5Cdfrac%7Be%7D%7B%5Cpi%7D%2B%5Cdfrac%7Be%7D%7B%5Cpi%5E2%7D-%5Cdfrac%7Be%7D%7B%5Cpi%5E3%7D%2B%5Cdfrac%7Be%7D%7B%5Cpi%5E4%7D-%5Cdfrac%7Be%7D%7B%5Cpi%5E5%7D%2B%5Cdots%3D%5Cleft(%5Cdfrac%7B%5Cpi%7D%7Be%7D%5Cright)%5E%7B5%7D">

### 2. Uma pequena equação. Una pequeña ecuación. 

<img src="https://render.githubusercontent.com/render/math?math=%5CLARGE%206%20%5Csqrt%5Bx%5D%7B9%7D%20-%2013%20%5Csqrt%5Bx%5D%7B6%7D%20%2B%206%5Csqrt%5Bx%5D%7B4%7D%20%3D%200">


### 3. O que faz este código de Octave?

```octave
a = 1; b = 5;
expo = 10

xr0 = (a * fun(b) - b*fun(a))/(fun(b)-fun(a));

epsilon = 10^(-expo); 
xr = xr0 ;

c = 0; 
itmax = 20;

while fun(xr)>epsilon 
  
  if fun(a)*fun(xr)<0
    b = xr;
  else
    a = xr;
  endif
  
  xr = (a * fun(b) - b*fun(a))/(fun(b)-fun(a));
  
  c = c+1;
 
  if c>itmax
    break endif
endwhile

function y = fun(x)
  y = (1/log(x+1.2))-(0.025*(x-1)^2.3);
endfunction
```

### 4. Tendrá salución única?, algún método directo?

<img src="https://render.githubusercontent.com/render/math?math=%5CLARGE%20x%5E%7Bx%7D%5E%7Bx%7D%20%3D%20%5Cleft(%5Cfrac%7B1%7D%7B2%7D%5Cright)%5E%7B%5Csqrt%7B2%7D%7D">
