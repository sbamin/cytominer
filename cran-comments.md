## Test environments
* local OS X install, R 3.3.3
* ubuntu 14.04.5 LTS (on travis-ci), R 3.4.1
* win-builder

## R CMD check results
There were no ERRORs or WARNINGs or NOTEs for OS X and ubuntu.

There is 1 NOTE on winbuild:

- *New submission*: This is my first submission!

- *Non-FOSS package license (file LICENSE)*: The LICENSE is BSD-style (BSD-3). It had to be edited to make it compatible with licenses of other software distributed by the Broad, e.g. https://github.com/CellProfiler/CellProfiler/blob/master/LICENSE, which available at https://pypi.python.org/pypi/cellprofiler


There is 1 WARNING on winbuild:

- *Files in the 'vignettes' directory newer than all files in 'inst/doc': 'cytominer-pipeline.Rmd'*. I don't know what to do about this one. The `vignettes` directory contains only `cytominer-pipeline.Rmd` on my computer. I suppose this warning crops up once the `cytominer-pipeline.R` and `cytominer-pipeline.html` get generated.


## Downstream dependencies

There are currently no downstream dependencies for this package.
