
---
title: "Sample Radar Charts" 
author: "Author: Sarah Allen"
date: "Last update: 11 April, 2019" 
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


<!--html_preserve--><div id="htmlwidget-2df31d066574d9e39e7f" style="width:100%;height:500px;" class="ramcharts_base html-widget"></div>
<script type="application/json" data-for="htmlwidget-2df31d066574d9e39e7f">{"x":{"chartData":{"export":{"enabled":true},"categoryField":"label","dataProvider":[{"label":"Release Process","now":4,"soon":4},{"label":"Development Process","now":4,"soon":4},{"label":"Dependencies","now":4,"soon":4},{"label":"Vulnerability Comms","now":1,"soon":3},{"label":"Security Team","now":1,"soon":3},{"label":"Ecosystem Need","now":4,"soon":4},{"label":"Adoption","now":1,"soon":3}],"graphs":[{"animationPlayed":false,"lineColor":"","fillAlphas":0.5,"bullet":"bubble","balloonText":"<b>[[title]]<\/b><br>[[category]] : <b>[[value]]<\/b>","title":"now","valueField":"now"},{"animationPlayed":false,"lineColor":"","fillAlphas":0.5,"bullet":"bubble","balloonText":"<b>[[title]]<\/b><br>[[category]] : <b>[[value]]<\/b>","title":"soon","valueField":"soon"}],"legend":{"position":"left"},"type":"radar","valueAxes":[{"gridType":"polygons","minimum":0,"maximum":4}]},"background":"#ffffff","listeners":null,"axes_listeners":null,"axes_listenersIndices":null,"categoryAxis_listeners":null,"chartCursor_listeners":null,"dataSetSelector_listeners":null,"legend_listeners":null,"panels_listeners":null,"panels_listenersIndices":null,"periodSelector_listeners":null,"valueAxes_listeners":null,"valueAxes_listenersIndices":[],"group":null,"is_ts_module":false},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->

<!---
# Error in legend(position = "left", useMarkerColorForLabels = TRUE) : 
#  unused arguments (position = "left", useMarkerColorForLabels = TRUE)
# when using this syntax from: https://datastorm-open.github.io/introduction_ramcharts/convert.html

legend_obj <- legend(position = "left", useMarkerColorForLabels = TRUE)
amRadar(data = data, legend = legend_obj, pch = "bubble", export = TRUE) 
-->


<!--html_preserve--><div id="htmlwidget-6e7a9fd82b1418c5edc9" style="width:100%;height:500px;" class="ramcharts_base html-widget"></div>
<script type="application/json" data-for="htmlwidget-6e7a9fd82b1418c5edc9">{"x":{"chartData":{"categoryField":"label","dataProvider":[{"label":"A","Product1":1,"Product2":2,"Product3":1},{"label":"Z","Product1":2,"Product2":8,"Product3":1},{"label":"E","Product1":3,"Product2":1,"Product3":2},{"label":"R","Product1":4,"Product2":1,"Product3":2},{"label":"T","Product1":2,"Product2":0,"Product3":4}],"graphs":[{"animationPlayed":false,"lineColor":"","fillAlphas":0.5,"bullet":"round","balloonText":"<b>[[title]]<\/b><br>[[category]] : <b>[[value]]<\/b>","title":"Product1","valueField":"Product1"},{"animationPlayed":false,"lineColor":"","fillAlphas":0.5,"bullet":"round","balloonText":"<b>[[title]]<\/b><br>[[category]] : <b>[[value]]<\/b>","title":"Product2","valueField":"Product2"},{"animationPlayed":false,"lineColor":"","fillAlphas":0.5,"bullet":"round","balloonText":"<b>[[title]]<\/b><br>[[category]] : <b>[[value]]<\/b>","title":"Product3","valueField":"Product3"}],"type":"radar","valueAxes":[{"gridType":"polygons"}]},"background":"#ffffff","listeners":null,"axes_listeners":null,"axes_listenersIndices":null,"categoryAxis_listeners":null,"chartCursor_listeners":null,"dataSetSelector_listeners":null,"legend_listeners":null,"panels_listeners":null,"panels_listenersIndices":null,"periodSelector_listeners":null,"valueAxes_listeners":null,"valueAxes_listenersIndices":[],"group":null,"is_ts_module":false},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->
