# realTimeGrapher
quick and easy real time graph display 

I got tired of spinning up little debug graphs in excel. So I made a super simple and (relatively) efficient way to graph live data, including:
* Sliding window graphs
* Multi Line Graphs
** Including independant legends per line (placement is iffy though)
* Save to file (png default)
* Dymanically growing graphs based on total samples.

In my testing it usually takes ~30ms to add a point to any of the graph types, so this works great for sampling frequencies above 10points/second. Example code for different use cases are listed at the bottom of the python script.

Hope this saves you time too :)
