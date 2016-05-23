Link Counter
------------
Author: Vance Piscitelli

This program is attempting to count the number of links it takes to get between two websites and show the path. My original version would only request a single webpage at a time, wait for a response, and then continue. To wait for every single webpage and not do anything in the meantime is rather slow so I'm starting to work on adding threading. By using threading, I can request multiple webpages at the same time which will help performance.

This program is similar to the traveling purchaser/traveling salesman problem that are NP-hard problems. Due to this complexity, I'm going to change my goal to instead of finding the best solution, to a "good" solution, something that results in a path between the source and destination websites. The internet is a big place and this change will make finding a solution easier than doing a breadth-first search over the entire internet until a solution is found.
