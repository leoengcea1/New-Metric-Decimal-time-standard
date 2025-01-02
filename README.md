# New-Metric-Decimal-time-standard
A new proposal for a better standard for the Metric/Decimal time implementation.

This here intends to make a better standard than the past proposed metric time
that you can see here:
	https://en.wikipedia.org/wiki/Decimal_time
	https://metric-time.com/

	https://it.wikipedia.org/wiki/Tempo_metrico

In resume,  my proposal is to use the same measure of time for the second as we use in the babylonian time (the currently used)

The biggest mistake that I see in the anterior proposal is to change the measure of the second. They tried to make another unit as 0.864seconds. This was bad because all the other units in S.I.  is based on this second measure that we use. 
So imagine as an example that 50Hz means 50 oscillations in a second . by changing to other measure like the past 0.864metric second .. Well, I'll not prolong but one would have to recalculate any hertz measure for that new second base ,and this also for m/s in velocity and any other unit that is based on the second of time.
They in the past wanted to change the second measure to make a day that fit in a 10 metric hours division. But this is not the most important factor. And this is proved by the past system proposed not having been succeeded in implementation.

So by maintaining the second base and using the 100s per minute and 100m per hour , we keep this second and the day will still have 86400s . Which will make 8 metric hours and 64 metric seconds .

This still maintains the advantages of metric time of being able to calculate faster and more clearly the time except the advantage of dividing the day in whole hours. 

So to convert to get an idea . 
this 1 metric minute of 100 seconds will have 1m40s of babylonian minute ãbout a minute and half
And 1 metric hour of 100 minutes will have 10’000s , 10^4 s , 2.777 bab hours of babylonian time.
About ~3 hours.


Why it's better:
 to think about, for example, Specs about a water pump if it pushes 32.7 ml per second just by looking you can see that it will push 327’000ml per metric hour . Now calculate how much ml per babylonian hour it pushes ? … you will need to multiply by 3600 , it's not so fast and direct just by looking at it right.

This standard intends to make for more efficient use of time metrics, faster and simpler estimations. Etc . It makes simple and efficient coding without needing to calculate and less confusion when dealing with time metrics in softwares. etc


so the units or amounts of measures proposed in this work here and all based on the second would be :


daycents = 864 seconds (aproximately ) 1/100 day . (day being aprox 86400.002s )

decimal minutes = 100 seconds

decimal hour = 100 minutes = 10000 seconds


it's good to call decimal to be more clear and differentiate from the older (proposed in french revolution) metric minutes that are based in another measure for seconds that would be 0.864 babylonian second

and notations

1 dc

1 md

1 hd


being 'md hd' better because in many latin languages the adjective "decimal" goes after the noun . and because making	'dm , dh' would be ambiguous and meanings d as deci, and m , h could be confused for the units m - meter , h- henry(inductance) .like dh , dm , could be confused as decimeter and decihenry.


To-do : 

datetime : libraries for programming languages supporting this .
