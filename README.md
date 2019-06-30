# DD-AVX Library: Library of High Precision Sparse Matrix Operations Accelerated by SIMD AVX2

## About
DD-AVX$B$O9bB.!&4JC1$J%$%s%?%U%'!<%9$G(BDouble / Double-Double$B@:EY$rAH$_9g$o$;$F;H$&$3$H$rL\E*$H$7$?%i%$%V%i%j$G$"$k!#(B

AVX2(+FMA), OpenMP$B$K$h$k9bB.2=$,$5$l$F$$$k!#(B

$B8=>u$G$O!"(BAVX2$B$d(BOpenMP$B$NL58z2=$O$G$-$J$$!#(B(OpenMP$B$N%9%l%C%I?t$rJQ99$7$?$$>l9g$O4D6-JQ?t$K$F9T$&$3$H(B)

# Build and Install

$B0J2<$N%3%^%s%I$G%S%k%I$*$h$S%$%s%9%H!<%k$,$G$-$k(B:

```
> make
> make install
```

submodule$B$H$7$F%9$+$i1i;;$N$?$a$N(BQD$B%i%$%V%i%j$,I,MW$G!"(B`make`$B$G(Bgit$B$r;H$C$F<+F0E*$K%@%&%s%m!<%I$5$l$k!#(B
$B%$%s%9%H!<%k@h$O(B`DD\AVX_DIR`$B$*$h$S(B`DD_AVX_INC`$B$K$h$C$F;XDj$G$-$k!#(BQD$B$b$3$3$K%$%s%9%H!<%k$5$l$k!#(B

### Document

Doxygen$B$K<+F0@8@.$5$;$F$$$k$,!"Bg$7$?%3%a%s%H$O=q$$$F$$$J$$!#(B
$B8=>u$G$O%X%C%@$rFI$s$@$[$&$,$-$C$HAa$$!#(B

include$B$NCf$O$=$l$>$l!'(B
* DD-AVX.hpp
BLAS / Sparse BLAS$B4X?t$N@k8@(B
* DD-AVX\_d\_spmat.hpp
$BG\@:EYAB9TNs7?$NDj5A(B
* DD-AVX\_d\_vector.hpp
$BG\@:EY%Y%/%H%k7?$NDj5A(B (std::vector<double>$B$r7Q>5$7$F$$$k(B)
* DD-AVX\_dd\_vector.hpp
$BG\!9@:EY%Y%/%H%k7?$NDj5A(B
* DD-AVX\_AVX2\_core/
AVX2$B2=$5$l$?(BDD$B$N(BAdd, Mul, $B@QOB1i;;$N<BAu(B

### Testing
$B%5%s%W%k$O$J$$$,!"3F5!G=$N%F%9%H$O0lDL$jB7$($F$$$k!#(B
`test`$B%G%#%l%/%H%j$K$=$l$>$lF~$C$F$$$k!#(B

```
> cd test; make 
```

## Restrictions
* BCRS$B7A<0$O$$$^<BAu$5$l$F$J$$(B
* SIMD/OpenMP$B$N@Z$jBX$($O$G$-$J$$!#(BMPI$B$b$J$$(B
* SIMD$B$NJQ?t(B`4`$B$,MW=j$KKd$a9~$^$l$F$$$k!#$3$l$i$O$$$:$l(B
* DD\*DD, D\*D$B0J30$N4X?t$N9bB.2=$K<jH4$-$5$l$F$$$k$b$N$,$"$k!#(B
