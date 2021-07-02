
<!-- README.md is generated from README.Rmd. Please edit that file -->

# dialektversum

<!-- badges: start -->

<!-- badges: end -->

The goal of `dialektversum` is to provide access to various packages
that translate German to German dialects.

## Installation

You can install the development version of `dialektversum` from GitHub
with:

``` r
#install.packages("remotes")
remotes::install_github("favstats/dialektversum")
```

``` r
library(dialektversum)
#> ── Attaching packages ──── dialektversum 0.0.1 ──
#> ✓ sachsr        0.0.0.9000     ✓ berlinr       0.0.0.9000
#> ✓ schwabr       0.0.0.9000     ✓ plattdeutschr 0.0.0.9000
#> ✓ hessr         0.0.0.9000     ✓ bayeRisch     0.0.0.9000
#> 
```

Currently `dialektversum` supports full-text translations into **6
German dialects**. They are:

## Swabian with [`schwabr`](https://github.com/favstats/schwabr)

``` r
get_schwab("Widerrechtlich abgestellte Fahrzeuge werden kostenpflichtig abgeschleppt.")
#> [1] "Widerrechdlich abgeschdellde Fahrglombe werda koschdenbflichdich abgeschlebbd."
```

## Plattdeutsch with [`plattdeutschr`](https://github.com/favstats/plattdeutschr)

``` r
get_plattdeutsch("Widerrechtlich abgestellte Fahrzeuge werden kostenpflichtig abgeschleppt.")
#> [1] "Gegend de rechtmäßig instellt Fahrtüüg warrt köstenafsleppt."
```

## Bavarian with [`bayeRisch`](https://github.com/favstats/bayeRisch)

``` r
get_bayerisch("Widerrechtlich abgestellte Fahrzeuge werden kostenpflichtig abgeschleppt.")
#> [1] "Widerrechtlich obgstäite Fahrzeig wern kostenpflichtig obgschleppt."
```

## Hessian with [`hessr`](https://github.com/favstats/hessr)

``` r
get_hessisch("Widerrechtlich abgestellte Fahrzeuge werden kostenpflichtig abgeschleppt.")
#> [1] "Widerreschtlisch abgeschdellt Fahrzeuge werrn kostenpflischtisch abgeschleppt."
```

## Saxonian with [`sachsr`](https://github.com/favstats/sachsr)

``` r
get_saxonian("Widerrechtlich abgestellte Fahrzeuge werden kostenpflichtig abgeschleppt.")
#> [1] "Widerreschdlisch abgeschdellde Fahrzeuge werden gosdenbflischdig abgeschlebbd."
```

## Berlin dialect with [`berlinr`](https://github.com/favstats/berlinr)

``` r
get_berlinerisch("Widerrechtlich abgestellte Fahrzeuge werden kostenpflichtig abgeschleppt.")
#> [1] "Widarechtlich abjestellte Fahrzeuje weaden kostenpflichtig abjeschleppt."
```
