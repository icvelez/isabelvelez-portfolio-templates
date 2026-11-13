| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Isabel Velez's Portfolio
This is my public portfolio for Telling Stories with Data at CMU! Welcome. 

# About Me!
I am currently pursuing a Master of Science in Public Policy and Management at Carnegie Mellon’s Heinz College, on track to graduate in May 2028. I am interested in social policy and public interest technology, and I seek to pursue a career as a policy analyst.

Growing up in Latin America, specifically Guatemala and Nicaragua, and seeing the institutional nature of inequality led me to pursue my B.A. in political science at Emory University. This ultimately led me here, because I want to learn how I can tangibly be a part of the policies that bring about change within those institutions.

# What I Hope to Learn
In Telling Stories with Data, I'm interested in learning more about how I can best communicate my findings in ways that are accessible to a variety of audiences while conveying what I want them to take away. I want to learn how to tell a story with data, so to speak, rather than present numbers and findings that don't have clear connections or tie into a broader meaning.  

# Portfolio

# Examples
In class demos and assignments: 

## Assignment #1: [Data visualization critique - AI Critique](Interest-in-buying-drones)
For this assignment, make sure you set up and link to a new page.  This page is linking to a new Markdown document called `visualizing-government-debt.md`.  For links to Markdown files in your repository, you can just include the name of the page without the `.md` extension. 

## Assignment 3&4: [Critique by Design](critique-by-design)
For this assignment, make sure you set up and link to a new page.  This page is linking to a new Markdown document called `critique-by-design.md`.  

## Makover Monday: Creating a New Data Visualization
Original data source: [MakeoverMonday Dataset](https://makeovermonday.vercel.app/dataset/2019w8)
<img width="1600" height="823" alt="image" src="https://github.com/user-attachments/assets/aee151c8-4480-4ec1-8a0b-bb8700c59b69" />

What stood out to me was that the visualization is a ranked horizontal lollipop chart, particularly in the shape of windmills. The fact that Texas utilizes a much larger amount of wind power in the U.S. is also clear, and stands out because of its sheer size and color. There are some components of the visualization that work well– we’re able to visualize which few states use the most wind power and how much the rest of the U.S. is dwarfed in comparison. These numbers are also demonstrated in the legend, highlighting the disparity between the major states and the rest of the country. 

However, while this is a creative and eye-catching visualization that matches the content that it is about, there are quite a few things here I don’t think work very well to represent the data. With the windmills, it is hard to tell what exactly the installed capacity of the states is. At the highest point of the windmills? There’s also visually a lot going on– there’s many, many states in this singular visualization and it is hard to see. This also creates clutter, making it overwhelming to look at and read. The total investment on the horizontal axis provides interesting measures, but that isn’t the main point of the visualization. There’s also a lot of data– it is telling us the installed capacity, but the legend is telling us the equivalent number of homes powered, and then the total investment is below. The vertical axis is also not evenly spaced, jumping from 100 to 1000, then to 5000. Overall, there’s a lot of different stories being told here and there’s not a very cohesive narrative. We also don’t know what it is we’re specifically supposed to take away because of that.  

I'd say the primary audience for this is likely aimed towards the general public, more likely people who are interested in renewable energy in the U.S. I think that the windmills and the design of the chart make it more approachable and engaging for a general audience, and it also lays out a large amount of data: the installed capacity, equivalent homes powered, and the total investment. However, I do not believe it is very effective in reaching that audience. The clutter, all the different types of data being presented, and the design of the “bars” make it difficult to tell what the precise numbers are. 

## My redesign sketch

<img width="1780" height="1152" alt="IMG_0012" src="https://github.com/user-attachments/assets/839c39ca-897f-4b07-8c8d-f16ba29ce72d" />

For my redesign, my goal was to limit the clutter by highlighting the states with the largest amounts of installed wind capacity. I sketched a lollipop chart, starting with the four states with the most wind capacity, followed by two average states in lighter colors. Below those, I included the combined installed capacity of the remaining states in grey and included the U.S. total in a callout.

However, I encountered a few issues as I was sketching. I found myself unsure of whether the color scheme was the most effective, and the "remaining states" bar that I made with the intention of being a comparison point to Texas turned out to draw attention away from it, creating the opposite effect. I also realized my math was slightly off-- it was in fact five states that held over half of wind capacity. The feedback I received from my peers was mainly about this "remaining states" bar. It was distracting, too dark, and a student mistook it for the horizontal axis. Another student asked me what the purpose of the three states below the top four was, and while I initially said that it was to demonstrate more "normal" states, I later realized the numbers weren't far off from California's. I didn't find them particularly useful, as I wanted the attention on the top states. 

## My final design

<div class='tableauPlaceholder' id='viz1794532791773' style='position: relative'><noscript><a href='#'><img alt='Five States Held Over Half of U.S. Wind Capacity in 2018Texas alone had 26%, more than the next three states combined' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wi&#47;WindCapacityin2018&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='WindCapacityin2018&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image'value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wi&#47;WindCapacityin2018&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'> var divElement = document.getElementById('viz1794532791773');var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width='100%';vizElement.style.height(divElement.offsetWidth*0.75)+'px'; var scriptElement = document.createElement('script'); scriptElement.src ='https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>


In my final design, I sought out to fix the issues I encountered above. First, I revised my math error and accounted for the five states that took up over half of U.S. wind capacity in 2018. I deleted the other states that were previously grey, and then added Missouri, the "median state" as a useful comparison point. I also decided to change my medium to a bar chart, since I find them easier to interpret more "standard" than lollipop charts. I added a bar of "remaining states" to see if I could make it work, but it was still distracting even if I made it lighter, so I decided to remove it. I figured that even without this comparison point, I could trust my audience to understand the massive scale of wind energy held by the five states (and Texas, in particular) regardless. I also chose to emphasize this in the subtitle, and in my annotation next to Missouri. Finally, I decided to change the color scheme of the five states. Texas is dark blue because it is in "first place", but the point I wanted to make was that they are a group! 

## Final project
Here it might be helpful to include a high-level description of your final project. 
[Part I](final-project-part-one)
[Part II](final-project-part-two)
Part III(final-project-part-three)

---
## Other stuff you can do (you can remove this section - it's just for your reference.)

### Changing text

You can change text, like this: 

**Here's some bold** text.  Here's some *italic* text. Here's some ~~strikethrough~~ text. 

### Creating tables

You can build tables like this: 

| Name         | Type of pet | Favority activity 1 | FA 2   | FA 3            | FA 4                                |
|--------------|-------------|---------------------|--------|-----------------|-------------------------------------|
| Eli          | cat         | Sleeping            | Eating | Being pet       | Plotting to overthow dog empire     |
| Howard       | dog         | You                 | You    | You             | Eating                              |
| Frankenstein | fish        | Swimming            | Eating | Blowing bubbles | Forgetting                          |

An easy-to-use template generator tool [can be found here](https://www.tablesgenerator.com/markdown_tables)

You can use different headings, like this: 

# Here's a large title (H1)
## Here's a subtitle (H2)
### ...and so on (H3)
You get the idea - just don't forget the space between the # and your title.  `#Title` won't work, but `# Title` will. 

### Adding images

Here's an example of how to add an image to my portfolio.  

![funny dog picture](funny-dog-unsplash.jpg)
> Photo by <a href="https://unsplash.com/pt-br/@charlesdeluvio?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">charlesdeluvio</a> on <a href="https://unsplash.com/photos/K4mSJ7kc0As?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

Alternately, you can set the size of the image using just a bit of HTML: 

<img src="funny-dog-unsplash.jpg" width="200"/>

Remember that you'll need to upload the image into your repository, or include a link to the image somewhere else.  

### Setting up a separate page

So here's the code you'll need to add to your own site to create a second page. 

1. First, create a new page in your repository (for example, dataviz1.md)
2. Next, add a link to that page by inserting the following into your readme.md page:

`[title](dataviz)` or `[dataviz](https://cmustudent.github.io/portfolio/dataviz.html)` or `[CMU](https://www.cmu.edu)`

Any of those formats will work. Here's some examples of working links: 

`[title](dataviz)` = [title](dataviz)  
`[dataviz](https://cmustudent.github.io/portfolio/dataviz.html)` = [dataviz](https://cmustudent.github.io/portfolio/dataviz.html)  
`[CMU](https://www.cmu.edu)` = [CMU](https://www.cmu.edu)   

Make sure to check these from your publicly accessible URL to make sure they're working correctly (not from the preview tab). 

Looking for more?  A nice Markdown guide [can be found here](https://www.markdownguide.org/cheat-sheet/)

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

