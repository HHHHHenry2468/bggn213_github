# Class 4 Lab
Xiaohe Li (PID 16354124)
Invalid Date

``` r
# This is my first R script
x <- 1:50
plot(x)
```

![](class04_files/figure-commonmark/unnamed-chunk-1-1.png)

``` r
plot(x, col='purple')
```

![](class04_files/figure-commonmark/unnamed-chunk-1-2.png)

``` r
plot(x, sin(x), col='orange')
```

![](class04_files/figure-commonmark/unnamed-chunk-1-3.png)

``` r
plot(x, sin(x), col='orange', type='l')
```

![](class04_files/figure-commonmark/unnamed-chunk-1-4.png)

``` r
plot(x, sin(x), col='orange', type='l', lwd=3)
```

![](class04_files/figure-commonmark/unnamed-chunk-1-5.png)

``` r
log(10)
```

    [1] 2.302585

``` r
log10(10)
```

    [1] 1

``` r
log(10, base=exp(1))
```

    [1] 2.302585
