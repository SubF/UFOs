# UFOs

## Overview of Project - Purpose

This project expands on Dana's website by adding additional filters for her UFO sighting table. In addition to the original date filter, users can now filter for city, state, country, and UFO shape as well. This will help users narrow down the desired data easier.

## Results

The new filters we added are able to work in conjunction with each other. Shown below is the data filtered by the date 1/1/2010 which yields several results.
![This is an image](https://github.com/SubF/UFOs/blob/main/static/images/datesearch.png)

By adding in a secondary filter, the user can narrow down the results further such as adding a state (ca) as shown below.
![This is an image](https://github.com/SubF/UFOs/blob/main/static/images/datestate.png)

If the user would like to narrow down the results even more additional filters can be added such as UFO's in the shape of a light
![This is an image](https://github.com/SubF/UFOs/blob/main/static/images/datestateshape.png)

## Summary

Although adding more filters is a step in the right direction, there are still several improvements that can be made. 

### Drawbacks
The main drawback in these filters is the rigidity of the filters. As shown below, typing in a state abbrevation in caps such as CA will not return California sightings because in the data California is lowercase ca. This applies to all of the filters since they are looking for an exact match.
![This is an image](https://github.com/SubF/UFOs/blob/main/static/images/2022-07-27%2021_12_06-UFO%20Finder.png)

### Recommendations
1. Have the filter accept a wider range of searches such as lowercase vs capital, space vs underscore or dash. A date range would also be extremely helpful to pull data for weeks, months, years etc.
2. Add either a drop down with possible search options or a list of suggestions should populate as a user types. Ex: Typing C in state would suggest CA and CT.
