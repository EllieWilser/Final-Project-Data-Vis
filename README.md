# Final Project Documentation
## Ellie Wilser

When I started creating my visualization, I wanted to answer, “What states produce the most profit from sales, and what products are the top profiting products?” As you will see, I started with very complex visuals, and I decided to simplify, not due to a lack of coding skill but because of ease of reading. I wanted my audience to see what states produced the most profits, what years were the most profitable, and what categories generated the most profit.

## Design Process

### Version 1

![Alt text](Sketch_V1.png)

For my first version, I wanted to include as many visualizations as possible. I realized that all these different charts and graphs made the page overwhelming. I went with the map because it was the most effective in showing which states were the most profitable. At this point in the process, I thought I was going to give up on showing profit by category, year, and the top-selling products.


### Version 2
![Alt text](Sketch_V2.png)

In version 2, you can see that the visualizations are simple due to removing the bar graph and the chart. This was too simple for me, and I wasn’t going to give up on the other parts of my questions.

### Version 3 / Final Version
![Alt text](Sketch_V3.png)

The main difference between version 3, and version 2 is the top products included in the tooltips of the map. After doing some research on tooltips in D3, I learned I could aggregate data inside of the tooltips which allowed me to include other information besides state name and profit. At this stage, I perfected the filters which allowed the user to see the differences in profit by each year and category. I also removed the subcategory because I found it too niche.


## Rational of Design Choices

### Encoding 

Location of Sale—I encoded the location of the sale to a map because it's easier to read than a list of state names or a bar graph. The viewer can easily see which states are the most profitable compared to a table or bar graph on the map. 

Profit—I encoded profit to color because it is easily grasped that a darker green color represents making more money, and the linear scale legend adds to this.

Profitable Product and Profit from Top Product - These were put into tooltips instead of creating an extra bar graph or table because I wanted to keep the visualization simple and easy to read. Also, this allows the most profitable products by state.

### Layout
 
I played around with the layout a lot when creating the visualization, but I decided to place the filters and legend at the bottom of the page instead of the top to have all the attention on the map. As seen in my original sketches, I had the filter at the top of the page, but I thought this took away from the map.

## Discovering Facts

The visualization allowed me to see that California, New York, and Texas were the states that generated the most profits and what products in those states were the most profitable. As seen in the documentation video, you saw which categories and years generated the most profits judging by the colors on the map.

