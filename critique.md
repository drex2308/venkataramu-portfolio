# Data Visualization Critique and Redesign

## Introduction
For this assignment, I selected a data visualization from [Our World in Data: Primary Energy Consumption per Capita](https://ourworldindata.org/grapher/per-capita-energy-use?tab=chart&time=earliest..2023&country=IND~SWE~OWID_WRL~USA~CAN~RUS~ATG~ASM~DZA). The aim was to critique the visualization using Stephen Few's Data Visualization Effectiveness Profile and then redesign it using Tableau.

## Original Visualization
![Original Visualization](energy-original.png) 
**Title:** Primary Energy Consumption per Capita  
**Source:** Our World in Data

### Why I Selected This Visualization
I chose this visualization because it provides a overview of per capita energy consumption from 1965 to 2023 across different countries. The topic is relevant for researchers, policymakers, and students studying global energy trends, making it an excellent candidate for critique and potential improvement.

## Critique using Stephen Few's Data Visualization Effectiveness Profile
In this section, I used Stephen Few's Data Visualization Effectiveness Profile to assess the visualization on various aspects. Below is a summary of my observations:

### **Usefulness:** 6/10
- The chart communicates long-term energy consumption trends effectively.
- However, it lacks contextual markers and factors influencing the data, limiting its usefulness for deeper analysis.

### **Completeness:** 5/10
- While the basic information (energy consumption over time) is present, the chart lacks additional context, such as the impact of GDP, policy changes, and energy sources.
- The visualization does not provide explanations for significant changes in trends.

### **Perceptibility:** 5/10
- The cluttered and overlapping lines make it difficult to distinguish trends, especially when many countries are selected.
- The heavy reliance on color can be problematic for those with color vision deficiencies.

### **Truthfulness:** 7/10
- The data presented appears accurate, but the title "Energy Use Per Person" is somewhat misleading. It suggests individual consumption when it represents average per capita use across all sectors.
- The fixed y-axis scale can obscure differences among countries with lower energy consumption.

### **Intuitiveness:** 6/10
- While the play-time-lapse feature provides some dynamism, the visualization lacks clear instructions or guidance on how to interpret trends.
- The use of country labels is clear, but it could be further improved with annotations.

### **Aesthetics:** 6/10
- The visualization is somewhat pleasing to look at, but the clutter detracts from its beauty. Simplifying the design could improve its aesthetics.

### **Engagement:** 5/10
- The visualization has the potential to draw viewers in, but the lack of context and clarity can hinder further exploration.

## Overall Observations
The visualization effectively provides a historical overview of global energy consumption per capita. The time-lapse feature and the ability to add or remove countries make it somewhat interactive. However, it suffers from clutter, overlap, reliance on color, and a misleading title, which reduce its overall effectiveness. 

### What I Would Do Differently
- Use cumulative average data to reduce clutter and improve comparability.
- Employ a diverging color palette and bar graph to address accessibility issues.
- Realign axes, countries on x-axis and the energy mesasure on y-axis
- A clearer title and country codes instead of long names.

## Redesign Plan
For the redesign, I created a horizontal bar chart wireframe that displays the average energy consumption per country from 1965 to 2023. This chart allows for a clear comparison of energy consumption across countries, avoiding the clutter of a line chart with overlapping lines. By sorting the countries in descending order, the chart makes it easier to identify the top energy-consuming nations at a glance.

<div class='tableauPlaceholder' id='viz1726712425913' style='position: relative'><noscript><a href='#'><img alt='Average Energy Consumption per country (1965 to 2023) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;cr&#47;critique_by_redesign&#47;AverageEnergyConsumptionpercountry1965to2023&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='critique_by_redesign&#47;AverageEnergyConsumptionpercountry1965to2023' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;cr&#47;critique_by_redesign&#47;AverageEnergyConsumptionpercountry1965to2023&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>
  var divElement = document.getElementById('viz1726712425913');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

The wireframe includes:
- A title that clarifies the timeframe and the metric: "Average Energy Consumption per Country (1965 to 2023)."
- Horizontal bars representing each country's average energy consumption in kilowatt-hours per person.
- A consistent x-axis scale to ensure fair comparisons between countries.

This new format addresses the issues of clutter and overlap in the original visualization while using an accessible layout.


### Step 4: Testing the Solution
I shared the redesigned bar chart with two individuals to gather their insights. Here is the feedback, distributed across both interviewees:

#### **Interviewee 1: Student, mid-20s**
- **What Worked:**
  - **Clear Top Countries:** Found that the bar graph format made it easier to identify the countries with the highest per capita energy consumption. The horizontal layout provided a straightforward way to compare between nations.
  - **Stable Metric:** Liked the use of average energy consumption per person over the entire timeframe, as it gave a clear basis for comparison and eliminated the clutter seen in time-series line charts.
- **What Didn’t Work:**
  - **Country Codes:** Found the use of country codes (e.g., "VIR," "ANT") confusing. Recommended using full country names for better clarity, as abbreviations made it harder to identify each country at a glance.
  - **Too Many Countries:** Pointed out that the number of countries made the chart very long and overwhelming. Suggested focusing on the top 20 countries to make the visualization more digestible and focused.
- **Questions Raised:**
  - "Is it necessary to include every country in this chart, or could it be more effective to highlight just a few?"
  - "Can the data be broken down by region to make the comparison easier?"
- **New Inspirations:**
  - Suggested adding a regional segmentation, grouping countries by continents to reveal global patterns more clearly.
  - Proposed changing the unit of measurement to something more relatable, such as "number of household appliances powered per person annually."

#### **Interviewee 2: Adult, late-50s**
- **What Worked:**
  - **Horizontal Bars:** Appreciated the use of horizontal bars, stating that it made cross-country comparisons clearer and was easier to interpret than the original line chart.
  - **Top Country Identification:** Noted that the new format provided a clearer view of which countries had the highest energy consumption per person.
- **What Didn’t Work:**
  - **Color Use:** Critiqued the uniform color of the bars, suggesting the use of a gradient or color scale to highlight differences in energy consumption more effectively.
  - **Headline:** Mentioned that the title could be more descriptive and engaging. Proposed changing it to something like "Top 20 Global Leaders in Energy Consumption Per Person (1965–2023)" to draw in the audience.
- **Questions Raised:**
  - "Could you change the unit to something more tangible, like 'average household energy consumption per person,' to make it more relatable?"
- **New Inspirations:**
  - Thought of the possibility of adding annotations to highlight key countries, explaining why they have higher or lower energy consumption.
  - Recommended using a race bar graph to show the changes in consumption over time, although acknowledged that this might be difficult to implement in Tableau.

#### **Summary of Feedback**
Both interviewees appreciated the switch to a bar chart for its clarity and ease of comparison. However, they pointed out areas for improvement, such as replacing country codes with full names, enhancing the color scheme, limiting the number of countries shown, and using a more engaging title. They also raised questions about regional breakdowns and using more relatable units of measurement, inspiring potential modifications for the final redesign.


### Step 5: Building the Solution in Tableau

