# ClmtAI
The red pill Generative AI model that show us what our future world will look like in
different climate change scenarios. ClmtAI will allow a user to ask using
natural language how a place on the world will look in the future under
different scenarios. To provide the answers, the ClmtAI model will leverage AI
climate models, satellite imagery, and existing landscape and cityscape
photography and videography. 

Below follows a mock up query that demonstrate the funcionality of ClmtAI.

> _Prompt:_ What will mount rainier look like in 2040 if co2 levels are not curbed globally?
> 
> _ClmtAI:_ Today, Mount Rainier, in Washington state, United States, captured by satellite 
> looks like, 
> 
> ![mount rainier from satellite](https://github.com/clmtai/clmtai/blob/main/images/mount_rainier_sat_now.jpg?raw=true)
> 
> From the ground at areas such as the beautiful Lake Placid, Mount Rainier looks like,
> 
> ![lake placid](https://github.com/clmtai/clmtai/blob/main/images/lake_placid_now.jpg?raw=true)
>
> Predicting exact appearances includes a great level of uncertainty. However,
> based on scientific research and advanced weather prediction models we can
> forecast what no decrease of CO2 from 2023 could look like.
>
> Increased CO2 levels will cause an increase of heat causing glaciers and snow
> to melt. Also, forest fires will become more prevalent in the pacific north
> west. Lastly, rainfall will become less frequent leading to desertification.
>
> Based on these factors, lake placid in 2040 could look like,
>
> ![lake placid future](https://github.com/clmtai/clmtai/blob/main/images/lake_placid_future.jpg?raw=true)
>
> With satellite imagery looking like,
>
> ![lake placid future](https://github.com/clmtai/clmtai/blob/main/images/placeholder.png?raw=true)
>
> This is the average scenario, you can ask for the upper and lower bound scenarios to get a better
> indication of the uncertainty of the predictions used in my modelling

Image sources: Google images, Google earth and Midjourney.


## Current status

We are just starting our journey! We will start as a open source project, it is
possible that some parts of the projects may be spun off as commercial
enterprises to help governments, NGOs, companies and/or individuals better
prepare for the impact of climate change.

## License / Philosophy

As the project founder, my intention is to build this project in the open. I believe that everyone should
be able to benefit from information on climate change to take action! The data that will be used in 
the open source variant will be NASA and ESA data that is licensed for non commercial purposes.

To fund the development we will also offer commercial services / products that
will be spinoffs of the core project. A commercial application could be natural language interaction
with geospatial data and climate model for various industries. Farmers could get better and easier insights 
into their field's yield and soil composition. Insurers and banks could get better risk levels of 
land devaluation due to drought or fire hazards for real estate portfolios. Cities could identify more
easily heat sinks and pollution levels. For the commercial offering we would use satellite imagery from
[Maxar](https://www.maxar.com/products/satellite-imagery) that has up to 30 cm per pixel resolution.


## Roadmap
Our roadmap will always consist of achievable and measurable targets that
allows us to learn more about the bigger problem we want to solve. Ideally, individual
targets will be formulated as [minimum viable products (MVP)](https://leanstartup.co/resources/articles/what-is-an-mvp/) 
that we can demo to potential clients. 

### MVP 1: natural language query on geospatial data
Our first MVP will allow to interact in natural language to query geospatial data. The goal will be
to develop an agent that could have the following conversation below limited to
the Netherlands only for phase 1 of MVP 1, and also USA for phase 2 of MVP 1.

#### Example conversation MVP 1

##### Example 1

> Q: What does mount rainier look like?
> 
> A: Mount rainier is a mountain with glaciers and snow surrounded by forests, this is a picture taken with Suomi NPP satellite,
> 
> ![mount rainier from satellite](https://github.com/clmtai/clmtai/blob/main/images/mount_rainier_sat_now.jpg?raw=true)
>

##### Example 2

> Q: How many parks are there in New York city?
>
> A: New York is a city in New York state, USA has 1,700 parks which cover 40% of
> the city based on Suomi NPP satellite.
>

##### Example 3

> Q: How is the crop yields changing in the province of Utrecht?
>
> A: In the province of Utrecht, the Netherlands, the crop yields in the past ten years have decreased by 10 %
> based on normalized difference in vegetation index captured by NASA lance. 

#### Data and scope MVP 1
The data and scope for MVP 1 will initially be limited to the USA and the
Netherlands. Both together account to respectively the number 1 and 2 largest
agricultural exporters in the world. Both have considerable data sources that
can serve as ground truth for any land segmentation work.  The firt sub MVP,
will start just on with the Netherlands, as the size of the country is much
smaller and allows for faster training, learning and iteration. 


#### Machine Learning scope MVP 1
For MVP the machine learning will be limited to geospatial data analysis and
machine learning and LLM fine tuning. The geospatial component is required to
convert satellite imagery and insights into a vector space that can be
understood by LLMs. The LLM fine tuning is required to allow natural language
queries to be run on the satellite data.

## Tasks for new joiners
If you want to join, here are some of the things we could be working on:
 
  - create onboarding guide to learn about Geospatial data analysis
  - create onboarding guide to learn about LLM fine tuning
  - create onboarding guide to learn about Generative AI models to create photorealistic images
  - create onboarding guide to learn about climate modeling with AI
  - create onboarding guide how to consume less energy with computing

and much much more! 

What you will get:

 - work on a problem that is very actual
 - learn new technology
 - work with an inspiring team where we want to improve the world

We welcome any background 🦄🌈!

## History

My, [Anton Bossenbroek](https://www.linkedin.com/in/abossen/) interest for Climate change and how we
communicate it comes from my passion for the outdoors and landscape photography. For an ongoing project on 
light pollution in the Netherlands, I started to develop a python package to analyse artificial light 
at night (ALAN). The package [pyalanisys](https://github.com/pyalanysis/pyalanysis) has been a bit 
in the mothballs due to a company that I founded. The summer of 2023 isn't yet finished and the incredible
spikes in climate extremes that we have [witnessed this year](https://www.theguardian.com/world/2023/sep/06/summer-of-2023-hottest-recorded-in-wake-up-call-to-cut-carbon-emissions)
made me really reconsider what I spend my time on.

Prior to starting this company I worked over 14 years developing and deploying
AI models for large companies throughout the world. Part of my experience was on deploying machine 
learning models to reduce downtime such as catastrophic failure in heavy
industries such as the Oil & Gas industry. I went in hoping to see that saved money would be invested
in the energy transition, unfortunately that was not the case. These
observations lead me to start my own company.

If this sounds interesting, drop a mail at: anton \<at\> bossenbroek.photo.


