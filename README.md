kickstarter-analysis
Module 1 Deliverable 3 Written Analysis
Overview of the Project
Module 1 was designed to get us familiar with reading data and extracting specific information from an excel file. We add more sheets to display our ability to add data and charts as part of the analysis.
Analysis & Challenges

Challenges & Difficulties
The first portion of the module was relatively easy to follow along if you paid attention to the directions step by step. The first difficulty I encountered was filtering categories because the filter was undone before I could extract data. It took me some time to figure out why my numbers were off, but it was an easy fix once I realized what my problem was. With VLOOKUPS, accuracy with the formula is key, and being an inexperienced excel user, coder, etc., I had to take my time with writing out the specific formulas. For example C2 in my Edinburgh Research sheet reads, =VLOOKUP(A2,Kickstarter!B:E,3,FALSE). For mean and median, again my filters were throwing off my numbers. I figured out that my filter was not on subcategory for “plays”. My Outcomes Based on Goals sheet took some time to work through since it was the formula with the most components, but eventually my formula for B3 came out to =COUNTIFS(Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<=4999",Kickstarter!$R:$R,"plays",Kickstarter!$F:$F,"successful") which served as a template for the rest.
Results
 
Theater Outcomes by Launch Date tells us that May was the most successful month. May, June, July, August, and October had similar numbers of failed campaign outcomes.

 
According to our chart, the percentage successful increases until the goal reaches 25,000 to 29,999 then decreases and flattens until goal reaches 40,000 to 44,999 and peaks at 45,000 to 49,999. And the percentage failed correctly mirrors those outcomes.
Limitations
The Theater Outcomes Based on Launch Date line chart clearly shows the overall trends throughout the year, but one limitation is that the range of 0-120 makes it difficult to pinpoint exact numbers for the outcome. A supplementary chart could be included of all the data, which would allow the viewer to find accurate numbers.
