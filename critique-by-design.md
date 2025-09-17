| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique By Design - Degree of Difficulty: Sport Rankings
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step One: The Visualization

This visualization was published on Page 2, an ESPN sports column that ran from 2000 to 2012. The primary audience is sports fans who are using the page for sports-related news. I chose this visualization because I was curious to see what sports were at the top and which were at the bottom. This is a topic that sports fan can continually argue about. 

[Sport Rankings](https://www.espn.com/espn/page2/sportSkills), Source: “Degree of Difficulty: Sport Rankings.” ESPN, ESPN Internet Ventures, www.espn.com/espn/page2/sportSkills.

## Step Two: The Critique

This visualization uses ten categories to rank the difficulty of sixty sports. I believe the categories effectively cover the most essential skills required in sports. The context of the ranking system is understandable; the viewer can easily interpret which sport is ranked number one. However, there are numerous sports and categories in this visualization, making it difficult to compare values. The repeating header is helpful, but there is just too much data. The ratings in this visualization were decided by an ESPN panel of experts. I think everything is presented truthfully, but one can probably argue the accuracy of each ranking as it's subjective. Regardless, I think the ranking system can be used, but with a caveat to explain it. This visualization utilizes a simple table, which is intuitive and easy to understand; however, with over 600 values, it’s a chore to look at, and the data gets lost within the chart. This is not the best visualization type for the data. Another con is the use of acronyms in the headers. The viewer can hover over them for an explanation or use the key at the bottom, but they’re not commonly known.  

This visualization was published on Page 2, an ESPN sports column that ran from 2000 to 2012. The primary audience is sports fans. I think this visualization reaches its audience less because of its cool and engaging design, which it lacks, but more because of the overall context of the chart. Ranking which sport is the most difficult within a sports news source draws engagement and brings value to its intended audience. This is a topic that people can argue and debate about. I chose this visualization because I was curious to see what sports were at the top and which were at the bottom. Additionally, by covering sixty sports, the chart is likely to include most people's favorite sport. 

In my redesign, I want to prioritize a comparison-friendly visualization. This chart provides a wealth of information, including its overall difficulty rankings and category values. In the original version, the overall rank is easy to compare, but the category values aren’t utilized. I want to be able to highlight the sports that lead in speed or hand-eye coordination, or the sports that get ratings under one. I think my biggest hurdle with this visualization will be figuring out how to maintain the scope of the data. There’s a lot of information, and it may prove difficult to keep all sixty sports and all ten categories and present them in an aesthetic way. 

## Step Three: Sketch a Solution

<div class='tableauPlaceholder' id='viz1758042949097' style='position: relative'><noscript><a href='#'><img alt='ESPN Panel Ranks Boxing the Most Difficult Sport. Where Does Your Favorite Sport Rank? ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cr&#47;CritiqueandRedesignSketch&#47;Heatmap&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CritiqueandRedesignSketch&#47;Heatmap' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cr&#47;CritiqueandRedesignSketch&#47;Heatmap&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1758042949097');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

My main goal with the redesign was to ensure my visualization allowed for easy comparison between values. To support this, I turned the original table into a heatmap. This made it easy to see whether values were on the high end (red) or low side (blue) without having to actually read the numbers. I chose red and blue based on the colors associated with hot and cold. Red is the color that represents a lot of effort or high values, while blue represents low effort or a lower threshold. I dropped the “total” column as this felt redundant given the rank column. I moved the rank column from the right end of the table to the side of the sport listings, so that the viewer can reconfirm that the sports are listed by their rankings. I tried to craft the title to both tell something about the chart while inviting the viewer to interact with it. 

<div class='tableauPlaceholder' id='viz1758042998943' style='position: relative'><noscript><a href='#'><img alt='ESPN Panel Ranks Boxing the Most Difficult Sport. Where Does Your Favorite Sport Rank? ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cr&#47;CritiqueandRedesignSketch2&#47;Boxplot&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CritiqueandRedesignSketch2&#47;Boxplot' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cr&#47;CritiqueandRedesignSketch2&#47;Boxplot&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1758042998943');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

While the heatmap was good for comparison, I felt it didn’t fix the issue of information overload. I wanted a visualization that showed the range of the data without specifically indicating each individual value. I first attempted to create a range plot using Datawrapper, but I disliked how it didn’t clearly show the difference between clusters and outliers. To fix this, I decided to do a box and whisker plot. This was great because the box represents clusters in the data, and the whiskers and individual points show the outliers. This visualization doesn’t include a ranking, but I listed the sports by the difficulty ranking. I chose to use neutral colors as I wasn’t highlighting anything specific in the data. While this visualization isn’t good for comparing specific values from attributes, the box and whisker plot does display that sports ranked as more difficult typically have values on the higher end of the scale, compared to sports ranked at the bottom. Sports at the bottom have a lower average value per attribute, with one or two outliers on the higher end. 

## Step Four: Test the Solution

Critique By Design Interview Questions and Responses:

What do you think this visualization is about?
-	This shows the ranking of the difficulty of different sports, split by category

Who do you think is the intended audience for this?
-	I can see any sports fan taking a look at this chart on ESPN
-	Heatmap is for in-depth analysis, boxplot is surface view

Is there anything you dislike?
-	On the heatmap, I think that the columns can blend together, especially if they have similar scores 
-	I dislike the box plot because it is difficult to quickly figure out what sport is more or less hard than another just by looking at it. I find the heatmap better to quickly gain info

Is there anything you find confusing?
-	The box plot doesn’t show what values the sports are ranked on which make it difficult to judge the authenticity of the ranking  
-	More context needed on the color scale in the heatmap. Are low or high values better?
-	More context for ranking needed in boxplot. There is nothing that indicates what rank is sport is

Is there anything you would change or do differently?
-	I would add a black line that separates columns to more easily distinguish the colors on the heat map. I might also add a note that indicates the scores were out of ten for each category 
-	No real use of color in the boxplot. Add color to highlight certain things 
-	Allude to scale used for attributes in the title in boxplot

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._


## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
“Degree of Difficulty: Sport Rankings.” ESPN, ESPN Internet Ventures, www.espn.com/espn/page2/sportSkills.
Few, Stephen. “Data Visualization Effectiveness Profile,” 2017, 11. http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf.

## AI acknowledgements
I used AI to help me complete certain operations in Tableau.

