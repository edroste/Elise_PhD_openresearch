# Elise's PhD: Open Research

Hi! I'm currently doing my PhD at the University of East Anglia and would like to make my work as open and reproducible as possible. Creating this (still very very simple web page) is my first attempt at doing so. I've not made a publically accessible webpage before, so please bear with me until I hopefully develop it into something decent. 

The purpose of this page is to give a very simple and rough overview of what I'm working on, as well as showing you the sources of the data I'm using for my analysis and how I process them. 

For those following my work more closely (a.k.a. my supervisors - if there's anyone else, I'd love to know who you are so please get in touch!), this space is also where you can re-fresh your memory on what I'm up to, check what I'm doing with my data, and follow some of my trains of thoughts. Feedback is always welcome! 

I'm working on a bunch of different data sets, so I'll try to maintain a clear overview. 

Alrighty, so here we go... 

## What's My PhD About? 
VERY roughly, I am interested in what the role is of sea ice on the carbon uptake of polar oceans. For anyone reading this who is not (yet) acquainted with this field, I will later write a section on the importance and relevance (or I might refer to a blog I want to write... Also on the to-do list!). But for now suffice it to say that oceans take up a huge amount of carbon dioxide (CO2) from the atmosphere. Huge amount = about 25% of global emissions. Without them, we'd be in far bigger troubles by now. Amongst all the oceans on Earth, the polar oceans (i.e. the Arctic Ocean and the Southern Ocean) play a particularly important role, because they are regions that can take up a lot of CO2. Even though I have an interest in the Arctic Ocean, I'm going to focus on the Southern Ocean from now on, as all the data I'm working on now relates to the latter. 

Out of all the anthropogenic CO2 that the global ocean takes out of our atmosphere, the Southern Ocean takes up about a third of it. This ocean is also the engine behind the global ocean thermohaline circulation and a gateway between surface waters (that are in contact with the atmosphere and can exchange gases) and the deep or bottom (even deeper) waters where heat and carbon can be stored (sequestration) for long periods of time. 

The extreme climatic conditions and sea ice make it very difficult to obtain year-round observations in the Southern Ocean, which is a barrier for oceanographers to properly understand the processes and mechanisms that drive the air-sea CO2 flux, export (what we call when water masses/carbon/other stuff is transported to the deeper parts of the ocean), and changes due to global climate change. 

## What Are the Data I'm Looking At? 
The two variables you'll probably read me going on and on most about are **dissolved inorganic carbon** (DIC) and **total alkalinity** (TA). These are two very important variables when it comes to discussing and analysing the marine carbonate system. For their definitions, I'm simply going to refer you to [Dickson et al.'s book (2007](https://www.oceanbestpractices.net/handle/11329/249). For TA, I'd like to refer you to [this paper by Wolf-Gladrow et al. (2007)](https://www.sciencedirect.com/science/article/pii/S0304420307000047?casa_token=l9KEEH2F3tUAAAAA:DlUwWpJ380wZq2nI4qHssJiCHWi1d2GoQsE2oBvf03pogfkOi8hzCjsh6anxa_8TQ6RU3j9K1w) (an *excellent* read!). So far, I've mostly been working on DIC and TA, because I measured these variables in a whole bunch of sea water samples and all the data processing (again, so far) has been done on these raw data. I'll tell you more about the quality checking etc. later. I'm of course also using CTD (conductivity, temperature, and depth/pressure) data from oceanographic CTD casts that also had water sampler-rosettes on them and a number of other sensors, such as fluorometers and oxygen optodes. 

There are two study areas that I'm currently working on: 

- Rothera Research Station (time series)
- Weddell Sea (oceanographic cruise)

Rothera is a British research station on the West-Antarctic Peninsula and is run by the British Antarctic Survey (BAS). They started to create a time series in 1997, called the [Rothera Oceanographic and Biological Time Series (RaTS)](https://www.bas.ac.uk/project/rats/), during which they sample and measure a whole array of variables that will over time give us insight into how this region is affected by the changing climate. Since 2010, they have also started sampling for DIC and TA. This time series from 2010 to 2014 has been published by Legge et al. [2015](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015GL063796) [2017](https://www.sciencedirect.com/science/article/pii/S0967064516303253). Samples for 2016-2017 have been analysed at UEA and I analysed samples between 2017 and 2019, also at UEA. It is these sample measurements that my processing scripts have transformed into something useful for analysis. 






