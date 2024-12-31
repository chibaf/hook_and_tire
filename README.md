# hook_and_tire

#力の活用 
https://youtu.be/eEni2Er38Po?si=SkRQ7HdTevHB4lY2 via @YouTube 
(力学を応用して筋力だけでは動かせないものを動かす)

## hook
<pre>
・フックの場合
１）初期値はフックを角度をつけて離す
２）力はフックがある角度になったら接線方向に加える（境界条件）
３）運動方程式は振り子
</pre>
$$
\frac{d^2}{dt^2}\theta+\frac{g}{L}\sin\theta=F_p \delta(\theta(t)-\theta_0)
$$
外力項は
$$
F_p \delta(\theta(t)-\theta_0)
$$
デルタ関数の公式
$$
\delta(f(x))=\sum_{j}\frac{\delta(x-x_j)}{f'(x_j)}
$$
を用いると、
$$
F_p\sum_{j}\frac{\delta(t-t_j)}{\theta'(t_j)}
$$
と書ける
## tire
<pre>
・タイヤの場合
１）地面に接したときに上方向に反発力が生じる
２）高さhの時に下方向に力が働く
３）運動方程式は重力場の中の等速運動
</pre>

## references
9.4: The Dirac Delta Function - Mathematics LibreTexts
https://math.libretexts.org/Bookshelves/Differential_Equations/Introduction_to_Partial_Differential_Equations_(Herman)/09%3A_Transform_Techniques_in_Physics/9.04%3A_The_Dirac_Delta_Function
