# Henrik Bengtsson's R Package Repository

This is my personal R package repository.  It contain the following R packages that are neither on CRAN nor on Bioconductor:

 * **[sfit]**

To install any of these packages, use:

```r
> install.packages("pkg-name", repos = "https://henrikbengtsson.github.io/drat")
```

I'll try to remember to provide Windows binaries when new versions of R come out.  If I forget, please post an issue.  I don't have access to macOS, so on that platform, you'll have to install from source (using the above command as above).


## Notes to myself

To add new versions of package *.tar.gz and *.zip files, use `drat::insertPackage()`, e.g.

```r
drat::insertPackage("sfit_0.3.1.tar.gz")
drat::insertPackage("sfit_0.3.1.zip")
```

Then add the new files to this repository, commit and push.  That's it.


[sfit]: https://github.com/HenrikBengtsson/sfit
