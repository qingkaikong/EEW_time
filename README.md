# EEW_time

This is a simple Demo of estimating Earthquake Early Warning alert time by giving the location, time of the earthquake and some locations. It is prepared by [Qingkai Kong](http://seismo.berkeley.edu/qingkaikong/) from [Berkeley Seismology Lab](http://seismo.berkeley.edu/). 

Note that: This is just a demo to show how to calculate the warning time from the earthquake early warning system. The numbers showing in the following example is not exactly the same from the real performance of the system in the earthquake. In this example, we can specify 3 different velocity models which will give you slightly different results in terms of the warning. 

It contains script to generate the following two plots:

1. A figure showing p and s waves from the M6.0 Napa earthquake in 2014. Distance from the epicenter is showing on the x-axis and the time since the origin of the earthquake is showing on the y-axis. P and s waves are shown as blue and red lines. A dotted line is showing the time of the earthquake alert sending out. Cities specified by the user will be plotted on the figure too, with a thick black line indicate the time from the alert to the time of the s wave arrive, this is the warning time. In this case, Napa Valley Opera House didn't get a warning because it is close to the epicenter and the warning sent out after the s wave arrives at this location.

![png](https://raw.githubusercontent.com/qingkaikong/EEW_time/master/figures/warning_time.png)

2. A figure showing alert time from the M6.0 Napa earthquake in 2014 on a map. Red star is the location of the earthquake. Blue dots are the cities specified by the user. The red circle is the blind zone where inside this zone, there will be no alert. 5s, 10s, 15s, and 20s warning zone is plotted on the map by the green circles.  

![png](https://raw.githubusercontent.com/qingkaikong/EEW_time/master/figures/warning_time_on_map.png)
