
---
title: "Sample Radar Charts" 
author: "Author: Sarah Allen"
date: "Last update: 09 April, 2019" 
output:
  html_document:
    toc: true
    toc_float:
        collapsed: true
        smooth_scroll: true
    toc_depth: 3
    fig_caption: yes
    code_folding: show
    number_sections: true

fontsize: 14pt
---

<!---
rscript -e "rmarkdown::render('data.rmd', c('html_document'), clean=FALSE)"
-->




```r
data <- data.frame(label = c("A", "Z", "E", "R", "T"),
                   Product1 = c(1, 2, 3, 4, 2), 
                   Product2 = c(2, 8, 1, 1, 0),
                   Product3 = c(1,1,2,2,4))
amRadar(data = data)
```

<!--html_preserve--><div id="htmlwidget-a42b7b45c7d2de612eca" style="width:100%;height:500px;" class="ramcharts_base html-widget"></div>
<script type="application/json" data-for="htmlwidget-a42b7b45c7d2de612eca">{"x":{"chartData":{"categoryField":"label","dataProvider":[{"label":"A","Product1":1,"Product2":2,"Product3":1},{"label":"Z","Product1":2,"Product2":8,"Product3":1},{"label":"E","Product1":3,"Product2":1,"Product3":2},{"label":"R","Product1":4,"Product2":1,"Product3":2},{"label":"T","Product1":2,"Product2":0,"Product3":4}],"graphs":[{"animationPlayed":false,"lineColor":"","fillAlphas":0.5,"bullet":"round","balloonText":"<b>[[title]]<\/b><br>[[category]] : <b>[[value]]<\/b>","title":"Product1","valueField":"Product1"},{"animationPlayed":false,"lineColor":"","fillAlphas":0.5,"bullet":"round","balloonText":"<b>[[title]]<\/b><br>[[category]] : <b>[[value]]<\/b>","title":"Product2","valueField":"Product2"},{"animationPlayed":false,"lineColor":"","fillAlphas":0.5,"bullet":"round","balloonText":"<b>[[title]]<\/b><br>[[category]] : <b>[[value]]<\/b>","title":"Product3","valueField":"Product3"}],"type":"radar","valueAxes":[{"gridType":"polygons"}]},"background":"#ffffff","listeners":null,"axes_listeners":null,"axes_listenersIndices":null,"categoryAxis_listeners":null,"chartCursor_listeners":null,"dataSetSelector_listeners":null,"legend_listeners":null,"panels_listeners":null,"panels_listenersIndices":null,"periodSelector_listeners":null,"valueAxes_listeners":null,"valueAxes_listenersIndices":[],"group":null,"is_ts_module":false},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->
