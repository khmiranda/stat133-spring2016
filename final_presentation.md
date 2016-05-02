---
title       : HTMN
subtitle    : 
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---




























--- &twocol

## HTMN: California Drought & Residential Water Usage 

**Question 1: How have CA drought conditions changed since the drought started in 2011?**

<!-- Limit image width and height -->
<style type="text/css">
img {     
  max-height: 560px;     
  max-width: 964px; 
}
</style>
 
<!-- Center image on slide -->
<script type="text/javascript" src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.7.min.js"></script>
<script type="text/javascript">
$(function() {     
  $("p:has(img)").addClass('centered'); 
});
</script>

*** =left width:90%
![plot of chunk unnamed-chunk-14](assets/fig/unnamed-chunk-14-1.png)

*** =right width:10%

![plot of chunk unnamed-chunk-15](assets/fig/unnamed-chunk-15-1.png)

--- &twocol 

**Question 2: How has residential water usage changed since the enactment of the statewide mandatory reductions in April 2015?**

*** =left width:70%
![plot of chunk unnamed-chunk-16](assets/fig/unnamed-chunk-16-1.png)


<table style="text-align:center"><tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="1" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td>Residential Water Usage (R-GPCD)</td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">policy_enacted</td><td>-19.982<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.475)</td></tr>
<tr><td style="text-align:left"></td><td></td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>17,066</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.772</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.766</td></tr>
<tr><td style="text-align:left">Residual Std. Error</td><td>28.689 (df = 16644)</td></tr>
<tr><td colspan="2" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"><em>Note:</em></td><td style="text-align:right"><sup>*</sup>p<0.1; <sup>**</sup>p<0.05; <sup>***</sup>p<0.01</td></tr>
</table>

***=right width:30%

![plot of chunk unnamed-chunk-18](assets/fig/unnamed-chunk-18-1.png)

--- &twocol

**Questions 3 & 4: Have penalties on urban water suppliers affected residential water usage? Since June 2015, have urban water suppliers been meeting their required conservation standards?**

*** =left width:50%
![plot of chunk unnamed-chunk-19](assets/fig/unnamed-chunk-19-1.png)


![plot of chunk unnamed-chunk-20](assets/fig/unnamed-chunk-20-1.png)
 


*** =right width:50%

![plot of chunk unnamed-chunk-22](assets/fig/unnamed-chunk-22-1.png)
