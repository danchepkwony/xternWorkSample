# Xtern Work Sample

## Introduction

I decided to follow the example 10-week activity plan of 10 weekly group dinners, 5 recreational activities, and one conference or Ted Talk event.

All of the workspaces have conference halls, but some don’t detail the capacity of their conference rooms. With this limited data and since we are conveniently hosted at IUPUI, Hine Hall Auditorium is the best choice.

For the recreational activities and group dinners, we’ll need to gather data on potential restaurants and venues.

## Methods

I used Google Map API to find nearby restaurants and recreational options for each workspace. Then, I found the top 20 nearby restaurants by user rating and the top 10 recreational options for each workspace. To find the top 20 restaurants, I filtered out restaurants with a price level lower than 1, which are usually fast food options. Then, I sorted the restaurants and activities based on rating. In addition, I computed the distance between the housing and each workspace.

The data collected is limited. Google Maps API only allows for 60 results per query. I could only receive 60 results from nearby restaurants. I made separate queries for each type of activity, so there’s a decent amount of data collected on activities. However, those queries were still limited.

With this data, we can now choose the best workspace.

## Results


## Conclusion

I believe Industrious Mass Ave is the best workspace for Xterns this summer. 
It is the most proximal to the housing, the highest top 20 nearby restaurant rating, and the lowest average distance for the top 10 rated nearby activities. 
The one concern I would have is the number of different activity types nearby. However, this number is based on Google’s Place types and limited to a 5 mile radius.
The benefits of this workspace outweigh the potential of having to choose two similar activities within a 5 mile radius or the minor inconvenience of looking further than 5 miles for a biweekly activity. 

