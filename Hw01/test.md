test
================

  - [Orange](#orange)
  - [Summary](#summary)
  - [Plot](#plot)

## Orange

Orange is a dataset about the growth of five orange trees. This is a
record of their trunk circumferences (in cm) at certain ages (in days).

The headers for the Orange dataset, as determined through the names()
function, are:

    ## [1] "Tree"          "age"           "circumference"

The full dataset, presented as a tibble:

<!--html_preserve-->

<div id="htmlwidget-a77e04797d05e1840e3a" class="datatables html-widget" style="width:100%;height:auto;">

</div>

<script type="application/json" data-for="htmlwidget-a77e04797d05e1840e3a">{"x":{"filter":"none","data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28","29","30","31","32","33","34","35"],["1","1","1","1","1","1","1","2","2","2","2","2","2","2","3","3","3","3","3","3","3","4","4","4","4","4","4","4","5","5","5","5","5","5","5"],[118,484,664,1004,1231,1372,1582,118,484,664,1004,1231,1372,1582,118,484,664,1004,1231,1372,1582,118,484,664,1004,1231,1372,1582,118,484,664,1004,1231,1372,1582],[30,58,87,115,120,142,145,33,69,111,156,172,203,203,30,51,75,108,115,139,140,32,62,112,167,179,209,214,30,49,81,125,142,174,177]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>Tree<\/th>\n      <th>age<\/th>\n      <th>circumference<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[2,3]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false}},"evals":[],"jsHooks":[]}</script>

<!--/html_preserve-->

## Summary

Here is a summary of the Orange dataset using the summary() function:

    ##  Tree       age         circumference  
    ##  3:7   Min.   : 118.0   Min.   : 30.0  
    ##  1:7   1st Qu.: 484.0   1st Qu.: 65.5  
    ##  5:7   Median :1004.0   Median :115.0  
    ##  2:7   Mean   : 922.1   Mean   :115.9  
    ##  4:7   3rd Qu.:1372.0   3rd Qu.:161.5  
    ##        Max.   :1582.0   Max.   :214.0

## Plot

And here is a plot of tree circumference versus age:

![](test_files/figure-gfm/plot-1.png)<!-- -->

Obviously we cannot conclude this is a linear relationship. However, the
goal here was simply to add a trendline, and that was a success\!
