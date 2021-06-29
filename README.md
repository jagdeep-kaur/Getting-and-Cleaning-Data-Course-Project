# Getting-and-Cleaning-Data-Course-Project
## Executing

### install packages 
* RCurl
* reshape2

### set working dir
* Script creates a relative `./data` dir in which it downloads the .zip, extracts it and writes the result file (`tidy_data.txt`)

### run `run_analysis.R`
* writes data to `./data` dir
* generates/overwrites `./CodeBook.md`
* `source('run_analysis.R')`
* global variables `tidyData` & `resultData` (see `CodeBook.md`)
