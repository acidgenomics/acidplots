# acidplots

[![Repo status: active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![Travis CI build status](https://travis-ci.com/acidgenomics/acidplots.svg?branch=master)](https://travis-ci.com/acidgenomics/acidplots)
[![AppVeyor CI build status](https://ci.appveyor.com/api/projects/status/ykti8ek8gj2i7g5r/branch/master?svg=true)](https://ci.appveyor.com/project/mjsteinbaugh/acidplots/branch/master)
[![Anaconda version](https://anaconda.org/bioconda/r-acidplots/badges/version.svg) ![Anaconda latest release date](https://anaconda.org/bioconda/r-acidplots/badges/latest_release_date.svg) ![Anaconda downloads](https://anaconda.org/bioconda/r-acidplots/badges/downloads.svg)](https://anaconda.org/bioconda/r-acidplots)

Functions for plotting genomic data.

## Installation

### [R][] method

```r
if (!requireNamespace("remotes", quietly = TRUE)) {
    install.packages("remotes")
}
Sys.setenv(R_REMOTES_UPGRADE = "always")
# Set `GITHUB_PAT` in `~/.Renviron` if you get a rate limit error.
remotes::install_github("acidgenomics/acidplots")
```

### [conda][] method

Configure [conda][] to use the [bioconda][] channels.

```sh
# Don't install recipe into base environment.
name="r-acidplots"
conda create --name="$name" "$name"
conda activate "$name"
R
```

[BiocManager]: https://cran.r-project.org/package=BiocManager
[Bioconductor]: https://bioconductor.org/
[Paperpile]: https://paperpile.com/
[R]: https://www.r-project.org/
[bioconda]: https://bioconda.github.io/
[conda]: https://conda.io/
