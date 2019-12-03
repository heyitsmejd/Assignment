# ESS Frontend Assignment
Develop two solutions that are cross-platform compatible and delivers the same functionality and styling that exists in the index.html page without the use of an iframe. 

## Getting Started
1. open index.html in an iframe supported browser to be able to see the iframe's content (ex: Chrome)
2. Code away!

## Requirements
* Come up with two solutions to solve this problem. 
* In the included README.md please include a brief explanation as to why each solution was chosen.
* ** The index.html styling should only be dependent on the main.css file. **
* ** The content that was previously rendered by the iframe should not be affected by the main.css file but should still have styling. **
* The solutions should be compatible across all browsers (Edge, IE, Chrome, Firefox, Mobile)


## For each solution please provide a brief explanation below.

For the first solution ( index.html )

I focused on replicating it as is, hard coding the div contents which ensuring everything works cross platform. I manually set up generic click listeners for each event, this helped me loop through and close similiar content when toggling specified items. The given exercise assignment, while functional, had a bug that wasn't closing all the divs upon opening a new modal. By manually adding and looping through my specified clicks, we could fix this issue relatively painless. For CSS, I moved to a flexbox setup for the content areas, this allowed easier positioning and better responsiveness cross platform, rather than hard coding absolute positioning.


For the second soltuion (second.html) 

I used the same styling as the first, however I've dynamically generated the content boxes and click listeners on the first page, to allow an easier time to add further content in the future.