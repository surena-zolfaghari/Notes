
list = {1, x, x^2, 5 x, 6 u}
list /. Times -> Power
list // TreeForm

g = ( {
   {1 - 2 m/r[], 0, 0, 0},
   {0, (1 - 2 m/r[])^-1, 0, 0},
   {0, 0, r[]^2, 0},
   {0, 0, 0, r[]^2 Sin[\[Theta][]]}
  } )


<< xAct`xCoba`
DefManifold[M, 4, {a, b, c, d, e, f}]
DefChart[sph, M, {0, 1, 2, 3}, {t[], r[], \[Theta][], \[Phi][]}, 
 ChartColor -> Red]
DefMetric[-1, metric[-a, -b], CD, {";", "\[Del]"}, PrintAs -> "g"]
ComponentArray[metric[{-a, -sph}, {-b, -sph}]]






