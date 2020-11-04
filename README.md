# Data Visualization Project
Martin Blatz
WPI
Fall 2020
Data Visualization

## Data
The data I propose to visualize for my project is from the [Fatal Police Shootings Database](https://gist.github.com/martinblatz/e7f1d853eec2cb8cafd3ffbdc068f494) compiled by the [Washington Post](https://www.washingtonpost.com).

## Prototype
I've created two proof of concept visualizations of the data set, shown below.

[![image](https://user-images.githubusercontent.com/68836117/94756820-8e11a280-0366-11eb-9801-81533672c616.png)](https://vizhub.com/martinblatz/b41be4226589490bb271121cc9488ca5)
The visualization shows the count of fatal police shootings represented in a stacked bar chart, categorized by race along the X axis and color coded based on the "flee" status of the victim.

[![image](https://user-images.githubusercontent.com/68836117/94756938-ed6fb280-0366-11eb-8206-afe7f4de55bd.png)](https://vizhub.com/martinblatz/eb72f6e679a64e49982b9f1440d0ef9e)
This graphic explores the second question in my previous assignment, "What is the demographic breakdown of fatal police shootings in the US, and how does it compare to the demographics of the entire US population?" In 2019, [US Census data](https://www.census.gov/quickfacts/fact/table/US/PST045219) shows that the U.S. is 60% white alone (not Hispanic or Latinx). The U.S. is 13% Black or African American alone, and 19% Hispanic or Latinx. Just under 3% of the U.S. identifies with more than one race. 

The visualization clearly shows that Black non-Hispanic and Hispanic individuals account for a much more significant percentage of shooting victims in the under 40 age ranges.

[![image](https://github.com/martinblatz/DataViz-project-proposal/issues/5#issue-735755876)](https://vizhub.com/martinblatz/3ec586d080e5447dbb0774aabc392acd)
This graphic is a later prototype of the bar chart which eventually become color coded to match the geomapped data and placed in the bottom right corner of the final visualization.

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

## Visualizations

## Open Questions
- What binning level is appropriate for this data when categorizing by age or date?
- Would it be more telling to transform the data to show representative data corrected for the racial or age demographics of the state or U.S. as a whole?
- I need to learn to map the data to a state location within a U.S. map. There appear to be some examples of a more basic mapping approach that may be used as a reference to build upon. 
- Combining this data set with U.S. and/or state demographics may be challenging and will require further research

## Imagine the Adjacent Possible
- I think it would be really interesting to be able to build the map referenced in the sketches above, but to be able to have a single visualization that allows the user to select a variable to populate the pie charts. The ability to perform advanced filtering based on the rich data set (age, gender, race, armed status, fleeing status) would be a great way to provide a more interactive data exploration experience. 
- If I could get sufficient city level data, it would be really interesting to see if there are any correlations between demographics, population, or political/voting tendencies and the volume of police shootings.

## Ideas for Interaction
- Create a menu/checkbox for each of the following categories: Flee status, armed status, signs of mental illness, and threat level. Use the menu or checkbox to filter data from the visualized data. This will enable the user to explore the data more thoroughly and look for patterns.
- A menu to switch between the categorical values represented by the visualization: age bin, race. The visualization will shift to group the data based on the selected variable. 
- Interactive highlighting where the user can hover over the legend and it will grey out all other values within the visualization.

## Schedule of Deliverables
- Week 7, October 14:
  - Initial data processing
    - Attempt to perform the age binning operation internally to the program, rather than prior to loading
    - Clean up null values within the data
  - Build a map of the US and add a simple marker to each state based on the total number of police shooting deaths in that state. This answers the question "Do fatal police shootings occur more often in certain parts of the country?"
- Week 8, October 21:
  - Build a pie chart component which can be placed anywhere on the map based on location
  - Refine existing bar charts
    - Detailed axis labels
    - Legend
- Week 9, October 28:
  - Filter based on
    - Flee status
    - Armed Status
    - Signs of mental illness
    - threat level
  - Menu to choose between grouping by age bin or race
  - Complete any debugging necessary
- Week 10, November 4:
  - Export to GitHub
  - DataVis portfolio video
