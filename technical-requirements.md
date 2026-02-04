Dear JASP enthousiast,

in order to get the most out of our upcoming hackathon, we encourage you to make sure:

- You have recent (ideally the latest stable) versions of R, RStudio and JASP
- You can install R packages from source. This may require:
	- [Rtools](https://cran.r-project.org/bin/windows/Rtools/) (in Windows)
	- [tools](https://cran.r-project.org/bin/macosx/tools/) (in mac)
	- For Linux users only:
		- Install `cmake` and `gcc-fortran`
		- Install `flatpak` (optional but recommended, it will allow you to not have to install additional R packages)
- If you don't have an account at GitHub.com, we advise you to [create one](https://github.com/signup)
- Additionally, we'd like to invite you join our Mattermost, our main communication channel. Click here (\*I'll add an alive link privately) to set-up your account.
- If possible, install the following CRAN packages:
```r
# From the R console
install.packages("renv")
pkgs <- c("remotes", "devtools", "testthat", "stringi")
renv::install(pkgs)
```
- If possible, install the following non-CRAN packages:
```r
# From the R console
remotes::install_github(c(
	"jasp-stats/jaspBase",
	"jasp-stats/jaspGraphs",
	"jasp-stats/jaspTools"))
```

Feel free to reach out in case you need help, either remotely or in person.

Looking forward to meeting you in Amsterdam!