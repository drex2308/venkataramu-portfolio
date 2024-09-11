# Visualizing government debt using Tableau

## Government Debt Bar Chart

General government debt is the gross debt of the general government as a percentage of GDP.

Debt is calculated as the sum of the following liability categories where applicable: currency and deposits; debt securities, loans; insurance, pensions and standardised guarantee schemes, and other accounts payable. A key indicator for the sustainability of government finance, changes in government debt over time primarily reflect the impact of past government deficits.

This indicator is measured as a percentage of GDP.


![Government Debt Bar Chart](export-2024-09-11T00_59_35.232Z.png)

[Source: OECD calculations on Governement Debt over the years]



## Government Debt Heat Map Published from Tableau


<div class='tableauPlaceholder' id='viz1726018553860' style='position: relative'><noscript><a href='#'><img alt='Countries keep raising thier debt over the years ! ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dh&#47;Dhanush_OECD_Government_Debt_HeatMap&#47;Countrieskeepraisingthierdebtovertheyears&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Dhanush_OECD_Government_Debt_HeatMap&#47;Countrieskeepraisingthierdebtovertheyears' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dh&#47;Dhanush_OECD_Government_Debt_HeatMap&#47;Countrieskeepraisingthierdebtovertheyears&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726018553860');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                  
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## Visualization of Government Debt using Tree Map

<div class='tableauPlaceholder' id='viz1726020896407' style='position: relative'><noscript><a href='#'><img alt='Countries keep raising thier debt over the last year! ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dh&#47;Dhanush_OECD_Government_Debt_TreeMap&#47;Countrieskeepraisingthierdebtoverthelastyear&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Dhanush_OECD_Government_Debt_TreeMap&#47;Countrieskeepraisingthierdebtoverthelastyear' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dh&#47;Dhanush_OECD_Government_Debt_TreeMap&#47;Countrieskeepraisingthierdebtoverthelastyear&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726020896407');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

The three data visualizations—bar graph, heat map, and tree map—each offer different perspectives on the same data, showcasing government debt levels across countries. Each visualization method has distinct advantages and challenges when it comes to conveying insights, as highlighted by Berinato's guidelines on crafting effective charts.

The ```Bar Graph``` provides a straightforward, linear comparison of countries' debt as a percentage of GDP. Its strength lies in its clarity; viewers can easily identify which countries have the highest debt levels, and the use of contrasting colors helps differentiate between countries. However, While crafting charts in clarity overly complex charts with too many data points can overwhelm the audience​. The bar graph starts to lose effectiveness as more countries are added, making it harder to interpret relative debt levels beyond the first few entries. This can be seen here as it requires scanning from left to right, which may cause ```visual fatigue``` with many data points.

The ```Heat map```, on the other hand, emphasizes temporal patterns by showcasing debt over time. This visualization method excels at capturing changes in debt levels across years and highlights countries that consistently remain at high or low levels. Clarity comes from simplifying visual clutter​, and the heat map does a good job by using a clear ```color gradient``` to represent values. The gradient makes trends easier to grasp quickly, but it may be challenging for viewers to compare exact values across countries ```without additional labels or clear demarcations```.

Finally, I chose the the ```Tree map``` because of its ability to show proportional relationships within a fixed space, allowing us to see the relative scale of debt between countries while also representing various subcategories in the data. Berinato's advice on controlling color​ is particularly relevant here, as the consistent ```use of shades within a spectrum``` effectively groups countries by debt magnitude without overwhelming the audience. The visual appeal of the tree map lies in its simplicity, making it easier for viewers to ```focus on larger insights rather than getting lost in the finer details```. This makes it a strong choice for high-level summaries where general patterns are more important than precise values, which is also a reason why for this visualization I have taken a subset of only ```one year```, and also removed any data points that were not visoible to ```remove any visual noise```.
