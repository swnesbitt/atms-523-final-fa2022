# ATMS 523 Final Exam
## Coding Problems

A client asks you to develop a frost risk model for their strawberry farm in Plant City, Florida.  As a first step in that process, you would like to understand the occurrence of these events by month and some information about the atmospheric conditions that generate frost in the location based on climatological records.  You remember that your ATMS 523 professor back in graduate school taught you some tricks that might be able to help. Using the code provided from Module 3, load in the GHCN-D daily temperature records from Plant City (Station `USC00087205`).

Use python code or a jupyter notebook to perform the following analysis:

1. Strawberries are planted around October 1 and ready for harvest by the end of January. What is the mean risk of frost and freeze, defined as the mean number of days per month over the period 1991-2020 that the temperature has been observed to be less than or equal to 32 and 28 degrees Fahrenheit, respectively, that might damage the plants for each month during this period at the GHCN-D site listed above?

1. To begin to explore the seasonal to sub-seasonal prediction of freeze events at this site,  using code you adapt from Module 4, obtain the monthly ENSO and NAO index for each freeze event identified in part 1.  Compute the number of freeze events for ENSO index values < -0.5, -0.5 to 0.5, and > 0.5, and print or display these values to a table.  Repeat for NAO index values in the same ranges. Do you see any relationship of freezes at this location with these two climate indicators?