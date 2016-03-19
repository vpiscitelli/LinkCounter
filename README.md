Link Counter
------------
Author: Vance Piscitelli

This program is attempting to count the number of links it takes to get between two websites. 
My original version would only request a single webpage at a time, wait for a response, and then continue.
To wait for every single webpage and not do anything in the meantime is rather slow so I'm starting to work on adding threading.
By using threading, I can request multiple webpages at the same time which has a signficant improvement on performance.
However, I'm still working on the threading to make it work smoothly because too many threads at the same time can cause issues too if I'm not handling them correctly.

