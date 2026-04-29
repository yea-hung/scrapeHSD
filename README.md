## Description

An R package for scraping facility data from the [Homeless Shelter Directory](https://www.homelessshelterdirectory.org/).  

## Installation

To install the package, use `install_github()` from the *remotes* package or `pkg_install()` from the *pak* package:

```r
pak::pkg_install('yea-hung/scrapeHSD')
```

## Use

Specify `state_name` and `state_abbreviation` in `scrape_hsd()`. For example:

```r
wyoming<-scrape_hsd('Wyoming','WY')
```
