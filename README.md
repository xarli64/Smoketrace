Smoketrace
==========


Description:

    Traceroute sourced monitoring with graphing and reporting.
    
    Smoke Ping alerts relate to latency events, Smoketrace alerts are path events.
    
    Future versions could incorporate latency monitoring and MTU monitoring to bring this into one tool 
    although I think it's best to keep them seperate. Smoke Ping could be extended to include other OWMAPs so the two
    tools' become more specialised in their respective fields and should aim to complement each other not conflict.



Who made it:

    James Bensley <jwbensley@gmail.com>



Why was it Mmade:  

    A similar concept to the infamous and brilliant Smoke Ping (http://smokeping.org/), but with traceroute!
    
    Every time I receive a smoke ping alert the first thing I do is run traceroute/mtr/etc to see where in
    the path the loss is occuring. If regular traceroutes where being run I would already know this.
                  

          
What is it used for:

    Smoketrace records the path to a destination (the IP address of the hops along the route to the target host)
    and alerts if an IP in the path changes or if the number of hops changes. This is to alert for path changes.
    

