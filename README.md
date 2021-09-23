# Older-Adults-Internet-Access-in-Rural-Urban-Suburban-Locations

This is an analysis of a cross-sectional sample from a third-party dataset. 
I wanted to see if there were differences in how older adults accessed the internet.

The original dataset is the Core Trends Survey dataset downloaded from https://www.pewresearch.org/internet/dataset/core-trends-survey/ 
The survey was conducted Jan 8 – Feb 2019 Original sample n = 1502 U.S. adults

My sample is n=466 U.S. adults ages 55 and up The lived in areas identified as "rural" or "urban and suburban") 
All used the internet or email, at least occasionally.
All had either a smart phone, a tablet, or a computer or a combination of these devices.
All had either high-speed internet access (like DSL, cable, or fiber optic) or cell phone or tablet access at home (no dial-up). So they either had high speed or cell connection (note the difference of these with latency issues and the rise of edge and fog computing in the future).

I used Excel to clean, sort, and delete data. I also created new columns with data to analyze. 
Since it was a third party dataset, I thoroughly explored the dataset to see what kind of data was collected. 
Most of it was categorical. (Ugh, numerical data is so much more fun to compute!!) 
The basic analysis was done in Excel (mean, count).

But since I had so much categorical data, I used RStudio to analyze the dataset. 
Most of the analysis was creating cross-tabs. And I used several R packages including tiny, janitor, skim, vtree, CGPfunctions.

I created several ugly, but meaningful data visualizations with the CGPfunctions packages.

I also used Tableau public to create a data viz of the map of the U.S., and counts and average ages of the sample participants. 
But again, there was not a lot of data that was numerical so I felt cross-tabs were the best way to analyze this dataset.

Overall (and probably to no surprise to anyone that has lived in a rural area), older adults that live in rural areas that have high speed internet access at home live a different lifestyle than older adults who live in a more urban setting.

This analysis stems from my interest in older adults' uses of mobile technology, which was the topic of my dissertation from years back.

