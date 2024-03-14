# electoral-college

## A Tableau storyboard of fully interactive dashboards of US electoral college maps and data

### About
A Tableau storyboard of four fully interactive dashboards of US electoral college maps and data (1789-2024). See the fully interactive storyboard of dashboard maps and graphs [hosted on Tableau Public](https://public.tableau.com/app/profile/nate.raese/viz/ElectoralCollege_17102638548600/ElectoralCollegeInteractiveStorybook).

### Overview
I began by constructing a Google Sheets spreadsheet (that I would later export in .xlsx format) of every single electee cast by elector by US state seperated out by sheet according to year. Where a state had more than one electee (i.e. the electors were split) multiple entries were created. After exporting, I connected my datasource in Tableau and began crafting the maps.

![Dashboard 1]()
There are are 4 finished dashboards on this storyboard. The first dashboard 'Interactive Electoral Map (1789-2020)' allows the user to navigate to any election year from 1789-2020; in doing so the map, the 'needs to win' bar graph, and the table infographic all adjust in real time, as does the interactive electee color legend. Where there is a pi chart instead of an elector count on the US map, select or hover over the pi chart to see the breakdown of split electors cast.

![Dashboard 2]()
The second dashboard 'My 2024 Predictions Map' is just what it sounds like: my predictions for how each state's electors will vote in the 2024 presidential election between the presumptive electees of Joe Biden and Donald Trump (as of the date of creation March 14, 2024). It will be interesting to come back at the end of 2024 to compare how close or far I was.

![Dashboard 3]()
The third dashboard 'Total Electors by State Map (1789-2024)' is similar to the first dashboard (and so features the table infographic) but is apolitical in the sense that the map simply measures the total electors per state — the state's fill color reflects this focus (therefore no electee bar graph). 2024 will have updated elector distribution, as is reflected in the map (gaining 2 is Texas; gaining 1 are Colorado, Florida, Montana, North Carolina, and Oregon; and losing 1 are California, Illinois, Michigan, New York, Ohio, Pennsylvania, and West Virginia.

![Dashboard 4]()
The fourth dashboard 'Electoral Journeys Graphed by State' allows the user to see a state's journey through the lense of number of electors given to it (the top graph) and to which parties those votes were cast (bottom graph). The history of the US unfolds on the horizontal axis, while the elector count is on the horizontal access. Not every state began at 1789 of course, and some states dip down to 0 for a short period (Civil War and Reconstruction). The history of the parties is displayed: thick lines stretching from green and orange and red show major parties, while points and blips signify short-fused third party ventures or faithless electors. Selecting or hovering over any line will reveal the detail of that specific point.
