([Final Project part 1](https://dhurst-cmu.github.io/Derek-Hurst-portfolio/final-project-part-one.html)
[Final Project part 2](https://dhurst-cmu.github.io/Derek-Hurst-portfolio/final-project-part-two.html)
[Final Project part 3](https://dhurst-cmu.github.io/Derek-Hurst-portfolio/final-project-part-three.html)


# Portfolio
This is my public portfolio for Telling Stories with Data at CMU!  Here's where all my cool work will go.  You should probably hire me. 

# About me
Im Derek! I Graduated with my BA in Political Science from Hiram College in December of 2023. I am a second year MSPPM Flagship hoping to learn more about better ways to utilize data!

# What I hope to learn
All the things - obviously. Maybe I want to make a list of all the things.  If so, I can do so in Markdown like this: 

1. How to more clearly make a visualization
2. Get a bit of experience using tablue
3. Understand how to make a graphic meaningful to different groups


# Portfolio
## Homework assignments
### Critique and Redesign

Part 1

  For this assignment the data I choose from Makeovermonday was a visualization from the platform Steam that visualized their current top 100 games by current players. I choose this because I use this platform often so thinking about how to change it would be something that would come easy for me. 

  when originally looking at the visualization from Steam there were a few things that stook out to me. The first was that I thought it served its purpose in letting people know what the current most played games were at the time. This was done in a table format by active player player count. This showed gamers what they were trying to. The list however was a bit though to actually use in the sense that you only saw a few of the games at a time and could not see the rest. Also the free and paid games were not split up which the platform does in other scenarios. I thought some easy distinction would make this better.

  The visualization that I critiqued can be seen here
  [Steam Most Played Games Chart](https://store.steampowered.com/charts/mostplayed)
  The data used in the new visualization I created can be found here
  [Steam Top 100 Played Games Dataset](https://data.world/makeovermonday/2025w3-steam-top-100-played-games)
Part 2 Sketching

  When Making Sketching out a solution there were a few things I wanted to accomplish
  1. Make a color distinction between prices
  2. Get more of the games on the screen so it is easier to see the difference in active players
  3. Remove software from the list as it is not a game

 This is what I came up with for a prototype
 <img width="1029" height="601" alt="Screenshot 2026-04-01 220259" src="https://github.com/user-attachments/assets/033de306-228d-4425-877f-b1284edc3234" />


 Part 3 Testing

 I went into testing thinging this was a good makeover of what Steam had done for their visualization but is that what others thought?

 I had two people look at the original sketch 

 Interview 1

 Gamer, early 20's
 Blue collar worker
 Has used the platform Steam

 What do you think of this visual?

 

 Can you tell me what you think the graph represents?

 - Top steam games right now.

 Is anything confusing?

  - Is it people who are playing right now or today

 Who do you think is the intended audience?

  - People looking at the steam store 

 What would you do differently

 -  I do not like the colors or the title I would change your title to be more specific

  Interview 2

  Student, mid 20's
  Student, MSPPM
  Took this class previously



  Can you tell me what you think the graph represents?

  - The amount of users playing games on Steam currently

  Is there anything confusing? 

  - There are a few things like not having game names or clear scale 

  Who do you think the intended audience is?

  - Gamers who want to know what games are doing well right now.

 What would you do differently

  - I would use a different color scale I do not think that a grey scale is good for showing price differences. I would also include player count on the bars to make it east to know.


Building a Solution

The Visualization that I ended up going with was still a bar graph as the data I was using from data.world could be good for trends over time but that was not something that I could do as there was not date category. I thought that showing this in a bar grpah format rather than the format that was used previously almost a table was good as it would one show more of the information at once and two becuase you could see the magnitude of difference between the games player bases. So going from this I wanted to include from the old vidusalization player count and price but the main thing I wanted to change here was visualizing the price difference in the different games that were at the top of the Steam leaderboard at the given time. 

<div class='tableauPlaceholder' id='viz1775098665012' style='position: relative'><noscript><a href='#'><img alt='Current Most Played Steam Games (01&#47;12&#47;2025)Source: data.world ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;SteamTop100games&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SteamTop100games&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;SteamTop100games&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1775098665012');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

When creating this data visualization the process was pretty rough for a minute. I had on making a data visualization that showed the changes in steam users and what they play over time but I did not have this data I had the data from one day. I went through several different visualization types such as tables or highlight tables but these also did not show what it needed to enough. So, I settled on a horizontal bar chart. When making this chart I had to keep a few things in mind an that was showing the rank somehow and the differences in those rankings. Doing this I went through a lot of trial and error finding the best way to show this. I ended up putting current players on the X axis as this would showing the ranking when put in ascending order. 

Shwoing the difference in prices was something I found more difficult as games have many different prices and they are never whole numbers for the most part. It took me an hour to think of how to do this well and ended up making bins out of the prices after going into excel and changing free to play variable to 0 and taking out $ signs. When I made bins this made it easy to put these games on a price scale that allowed it to be interpretable and easily with a bin index. Doing all of this allowed me to make this visualization that I think changed the concept for the better. 

When I thought of feedback I had been given through the two people I talked to it was clear a few changes were neccesary. I ended up making the colors as green for free and more red for more expensive. Something else good from the feedback was putting the numbers on the rows it this makes it easy to know exactly how many players were playing that specific game. 

The critique method helped as it allowed me to think about the different factors of the visualization and how they impact how the user will interpret the graph. When thinking about this it was clear that clarity and being able to quickly understand a lot about the graph quickly was important so these are the things that I focused on when trying to make this visualization better. 



## Final Project
[Final Project part 1](https://dhurst-cmu.github.io/Derek-Hurst-portfolio/final-project-part-one.html)
[Final Project part 2](https://dhurst-cmu.github.io/Derek-Hurst-portfolio/final-project-part-two.html)
[Final Project part 3](https://dhurst-cmu.github.io/Derek-Hurst-portfolio/final-project-part-three.html)


