# History Timeline



## Demo

https://history-timeline-bd1b5.firebaseapp.com/

## Description

The app is built with Polymer 2 and hosting on Firebase.

Enter a name of a famous historical figures in the top input box, click Search. The birth and death year will shown on the timeline below.

## Feature

- The app uses Wikipdia API to pull data.
- Autocomplete feature is implemented at name entering, quick call to Wikipdia api will return the closest historical figures's name.
- Birth, death year, thumbnail image and name of the historical figure will return from the Wikipdia api, and shown on timeline.
- Zoom in and zoom out button to toggle timeline scale, for more detailed or larger view

## Future improvement

- Currently only figures born after 0 A.D. can be found and display properly on the timeline. I am still working on figures born beofre 0 A.D
- The birth and death year are filtered from the return Wikipdia data in string. The strings are in many different format, a filter function is built that can get most of year data, but it still missing some format. I will work on the filter to include all format, so all search will work.
