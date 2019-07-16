# index analysis for intron retention paper

Run code below to generate `index_figure_4.pdf`.

```r
if (!require(INdEX)) devtools::install_github("shians/INdEX")
library(INdEX)

source("index_analyses.R")
```

The following useful objects will also be created:

* `index_cell_line`: the index analysis object for cell lines
* `index_immune`: the index analysis object for immune cells

See `str(index_cell_line, 2)` for an idea of the contents.
