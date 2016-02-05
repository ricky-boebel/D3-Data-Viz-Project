Udacity Project 6 completed January 2016

By Ricky Boebel

Dataset from: http://stat-computing.org/dataexpo/2009/the-data.html

Data: Airline data from 2001 of 5967780 flights. 

Summary: 
2001 brought on a paradigm shift for air travel. The attacks on the September 11th changed the industry, 
many americans chose to stop traveling the months after the attack. The above map shows the progression
month-to-month on the average delay per flight from each airport in the United States. We see delays dramtically
reduce from september on due to the drop and demand easing logistical pressure on airports. A secondary effect 
may have been airlines and passengers prioritizing timely departures and arrivals as a concerted effort for 
safetybAnother case for thisiousely. We see this effect is most pronounced on the east coast where the 
attacks took place.

Feedback index1.html: 
Person #1-The inclusion of Hawaii, Peurto Rico and Alaska reduce the visibility of the lower 48, where 99% of the data is from.
Person #1- Because every airport has a different amount of flights, its defficult to see the effects of 9/11
on air travel because it is relative to the number of flights before the attacks. 
Person #2- There is a certain amount of clutter when inluding every airport. Can't see major changes, espicially on the east coast.

Design Decisions:
- Zoom was applied to the lower 48 states to get a better feel for the size of the circles while animating.
- A month by month animation was chosen to show the changes thoughout the year as well as before and after
the attacks. 
- I knew from my research that many flights dropped but this did not come accross well in the map because the 
number of flights at each airport was just too large.
- I decided to focus on delays as a way to show both how efficentely airports were servicing customers. This time
I accounted for flights by creating an delay per flight(dpf) statistic. 
- I also only included airports with a minimum of 10 flights every day, to avoid small airports dominating the 
user's attention, with reletively insignificant delays.

Feedback index2.html:
Person #2- Positive feedback for the zoomed in window on the lower 48 states.
Person #2- Thought I needed a legend to explain the what the dots meant and to differentiate whether the flights are
delayed or on time flights.
Person #3- Adding interactivity, to compare data that is months apart.

Design Decisions:
- Created a colors variable, green circles for on time or early per flight average and red for delayed flights
- Added a buttons bar to switch from month to month after the animation to create a user-driven narative.
-placed legend on the left with custom circles.
