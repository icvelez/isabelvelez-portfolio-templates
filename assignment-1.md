| [Home Page](https://cmustudent.github.io/tswd-portfolio-templates/) | [Data Viz Examples](dataviz-examples) | [Assignment #1 - Visualizing Government Debt](assignment-1) | [Makeover Monday](makeover-monday.html) | [Final Project I](final-project-part-one) | [Final Project II](final-project-part-two) | [Final Project III](final-project-part-three) 

## Original visualization: [General government debt](https://www.oecd.org/en/data/indicators/general-government-debt.html) 

<img width="1248" height="672" alt="Screenshot 2026-11-19 at 10 47 53 AM" src="https://github.com/user-attachments/assets/8910c5aa-4029-4d8b-a022-a0c87529ab71" />

The original dataset can be found on the OECD's website, linked above. This is a time-series dataset that tracks government debt over time, and we can examine how public debt changes across different years and countries.

## Guided Design 
<div class='tableauPlaceholder' id='viz1795117367220' style='position: relative'><noscript><a href='#'><img alt='General Government Debt ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ye&#47;YearsandDebt&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='YearsandDebt&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ye&#47;YearsandDebt&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1795117367220');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


## My Redesign 
<div class='tableauPlaceholder' id='viz1795103503420' style='position: relative'><noscript><a href='#'><img alt='Which Countries Have Stayed Above 100% Debt-to-GDP?  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ye&#47;YearsandDebt&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='YearsandDebt&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ye&#47;YearsandDebt&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1795103503420');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

After creating the first visualization, what stood out to me were the countries that consistently stayed above 100% debt-to-GDP. To make these stand out, I chose the Top 6: Japan, Greece, Italy, Portugal, Belgium, and France. I chose to keep "OECD average country" as a benchmark, and then added a 100% line so that it would easier to see the countries above that mark. 

For a comparison or reference, I chose two other countries that had more "normal" amounts of debt and were below that line (Germany and Mexico). Then, I ensured that the Top 6 were distinct colors, made the OECD line a dark gray for contrast, and then Mexico and Germany lighter shades of gray. I initially had a legend, but found it was a bit inconvenient to look between the many colors and lines, so I instead added the country labels next to their respective lines. 

Though they are different graphics and had their own objectives, I believe that for the purpose of showing countries above the 100% debt-to-GDP threshold, my final graphic was more effective since there were less countries to parse through. This highlighted the stark differences between the countries with the highest amounts debt relative to their own economies, the average, and just how high above the 100% line that was. 

## AI acknowledgements
I used Claude to help me with my lines, more specifically, for guidance with adding labels to them and for setting their individual colors. 

