Introduction:
Base on the provided information from lecture, we decided to use wifi scan to make the of the automobile activity.
We set the scanner to scan 200 loops within 20 mins the result are showing in the plot below.



Background information:
Testing location: PHO113, the Raspberry Pi is located around 5 meters to the window.
Testing Time period: The testing period is Sep 16 2021, 7:00 PM to 8:00 PM
Testing times: 2 times, first time scan 100 loops, second time 200 loops.

Explanation:
base on the datas and plot we got from the wifi scanner, the activity the clear. I believe the distance from scanner to Highway is too far. 
There are maximum 7 devices in the 1 loop of scanning. If we get closer to the highway I believe the number of device will increase.

15mins scanning:
![15min](https://user-images.githubusercontent.com/52738892/133869264-d8d59829-8fce-4438-b6e2-e298c0b1dd5e.png)



10mins scanning:
![10mins](https://user-images.githubusercontent.com/52738892/133869280-af077b0f-9767-4c59-91ba-b783aae6d9c6.png)



Difficulties:
In the beginning, we have issue on ssh connect. After some research on the Pi Community, we solve all of the problems. later on the project, the most of time spend is on transfer python file between Mac and Pi. For the SCP method, we have trouble to locate the scan data on the Mac, we simply email the data from Pi to Mac to solve this problem.


Discussion:
In the data from two different scanning, there are many loops shows result that there are 0 wifi activity, which is wired, in our idea there are at least
school's wifi system are active. We are still looking for the reason.

What's New:
It is first time deal with Raspberry Pi and Python, we have learned some python basic and Raspberry Pi setting and connection.

First time know:
I first time know most of car have a wifi hotspot.


