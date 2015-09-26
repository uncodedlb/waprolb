{% if page.venue == "WELABS" %}

![WE Labs]({{ site.baseurl }}/images/WE_Labs2.jpeg)


### VENUE & MEETUP INFO  
**DATE:**  {{ page.date | date: '%a – %B %d, %Y' }}  
**TIME:** {{ page.meeting_time }}  
**LOCATION:**  235 E. Broadway, 8th Floor, Long Beach, CA  
**MAP LINK:** [WE Labs](http://www.welabs.us/contact) -- Broadway + Long Beach BLVD intersection.  
**PARKING:**
**FREE:** Street parking east of Long Beach Blvd after 6p.  [Metered until 6p](http://www.downtownlongbeach.org/parking).  WE Labs is on the corner.
**CHEAP:** [The Cityplace Lot C #6 ... 2hrs FREE then hourly](https://www.google.com/maps/d/viewer?mid=z-je1exzTCd4.koH8EDyrfmPg&msa=0&ie=UTF8&t=m&ll=33.76923,-118.189459&spn=0.01427,0.038581&z=15&source=embed) >> 3rd Street + Promenade


{% elsif page.venue == "GJ" %}


![GunnJerkins Offices]({{ site.baseurl }}{{ site.sponsors.venues.gj.image }})


### VENUE & MEETUP INFO

**DATE:**  {{ page.date | date: '%a – %B %d, %Y' }}  
**TIME:** {{ page.meeting_time }}  
**LOCATION:**  
{% if site.sponsors.venues.gj.logo != "" %}<img class="logo" src='{{ site.sponsors.venues.gj.logo }}' alt='{{ site.sponsors.venues.gj.name }}'>{% endif %}  
  [Gunn Jerkens Marketing Communications](https://j.mp/wapro-gj)  
  3950 Cover Street  
  Long Beach, CA 90808  

**MAP LINK:** [Map](https://j.mp/wapro-gj)  
**Directions from 405 FWY at Lakewood:** [Directions](https://j.mp/wapro-gj)  
**Instructions:**  Gunn-Jerkins building is on the South-East corner of Cover + Schaufele. Enter driveway on Shaufele (just South of Cover), then first building on left at the SE corner of the building. If you have any trouble finding the office, please call: 562-499-6707.  
{% endif %}
