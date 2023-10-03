# Cntrl_Eegin1_hw2









## p2.12
opne-loop transfer function(개방루프 전달함수)는 $\frac{Y(s)}{R(s)}$ = $\frac{K}{s+50}$ 이다  
$R(s)$ = $\frac{1}{s}$ 이기에 $Y(s)$ = $\frac{K}{s(s+50)}$ 이다  
부분분수로 나타내면 $Y(s)$ = $\frac{K}{50}(\frac{1}{s}-\frac{1}{s+50})$ 이고  
윗부분을 라플라스 변환을 하면 $y(t)=\frac{K}{50}(1-e^{-50t})$ 이다  
t가 무한대로 가면 $e^{-50t}$가 0으로 수렴하기 때문에 $y(t) \to  \frac{K}{50}$이다   
따라서 값이 1이 되기 위해서 K의 값은 50이다


## p2.15







## p2.37
(a) 두 개의 질량 시스템을 식으로 나타내면 $m_1\frac{d^2x}{dt^2} = -(k_1+k_2)x + k_2y$ and $m_2\frac{d^2y}{dt^2} = k_2(x-y)+u $ 이다  
식 조건에서 $m_1 = m_2 = 1, k_1 = k_2 = 1 $ 이라는 조건이 주어졌으니 대입을 해보면  
$\frac{d^2x}{dt^2} = -2x+y$ and $\frac{d^2y}{dt^2} = x-y+u $


















