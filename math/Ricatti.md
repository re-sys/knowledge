$P_{N}=Q_{f}$
$V_{N}=x_{N}^{T}P_{N}x_{N}$
$V_{k}=\min\limits_{u}x_{k}^{T}Qx_{k}+u^{T}Tu+V_{k+1}(x_{k+1})$
$V_{k}=\min\limits_{u}x_{k}^{T}Qx_{k}+u^{T}Tu+(Ax_{k}+Bu_{k})^{T}P_{k}(Ax_{k}+Bu_{k})$
$u_{k} = -(R+B^{T}PB)^{-1}B^{T}PAx_{k}$
$K=(R+B^{T}PB)^{-1}B^{T}PA$
$V_{k}=x_{k}^{T}(Q+A^{T}PA+K^{T}(R+B^{T}PB)K)x_{k}$
$P_{k}=(Q+A^{T}PA-K^{T}SK)$