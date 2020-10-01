# Data Visualization Project

## Data
The data I propose to visualize for my project is from the [Fatal Police Shootings Database](https://gist.github.com/martinblatz/e7f1d853eec2cb8cafd3ffbdc068f494) compiled by the [Washington Post](https://www.washingtonpost.com)

## Prototype
I've created a proof of concept visualization of this data. It's a ... and it shows ..

[![image](https://user-images.githubusercontent.com/68836117/94756820-8e11a280-0366-11eb-9801-81533672c616.png)](https://vizhub.com/martinblatz/b41be4226589490bb271121cc9488ca5)

[![image](https://user-images.githubusercontent.com/68836117/94756938-ed6fb280-0366-11eb-8206-afe7f4de55bd.png)](https://vizhub.com/martinblatz/eb72f6e679a64e49982b9f1440d0ef9e)


## Questions and Tasks
The following tasks and questions will drive the visualization and interaction decisions for this project
- Do fatal police shootings occur more often in certain parts of the country?
- Are racial or age disparities as they apply to police violence more evident in certain parts of the country?
- What is the demographic breakdown of fatal police shootings in the US, and how does it compare to the demographics of the entire US population?
- Are fatal police shootings becoming more or less common?

## Sketches

![image](https://user-images.githubusercontent.com/68836117/94757350-062c9800-0368-11eb-9e40-f0e97753a6b5.png)
This is a representative sketch showing a pie chart assigned to each state. Each pie chart will show the percentage of shootings in a given state broken down by race, age bin, armed status, and/or fleeing status. I envision this sketch as 4 separate charts that can be iterated across to provide more detail.  

![image](https://user-images.githubusercontent.com/68836117/94757428-2f4d2880-0368-11eb-8b4a-1b8440bc5c06.png)
This is an area chart that shows the total fatal police shootings over time. Each stacked area represents the number of victims for a different racial background. The sketch currently shows the data as a instantaneous total for a given time, but upon further thought I believe that a cumulative total makes more sense for this type of chart. Thus, each line will always either stay flat or rise as it moves to the right.

## Open Questions
- what binning level is appropriate for this data when categorizing by age or date?
- would it be more telling to transform the data to show representative data corrected for the racial or age demographics of the state or U.S. as a whole?
- I need to learn to map the data to a state location within a U.S. map. There appear to be some examples of a more basic mapping approach that may be used as a reference to build upon. 
- combining this data set with U.S. and/or state demographics may be challenging and will require further research

