Title: Grace M. Rodriguez
Date: 2015-05-24
Slug: grace
Category: People
Tags: Flows


#Biography
Hola!

My name is Grace M. Rodriguez, I'm a student at the University of Puerto Rico - Rio Piedras Campus and I'm currently transferring to Computer Science. I'm doing a research
at the university on Techniques for Anomaly Detection in IPv4 & IPv6
Network Flows with Dr.Humberto Ortiz-Zuazaga. In the semester of 2015, I was able to participate in the  Computing Sciences Summer Student Program (CS Summer Student) in the Computational Research Division at Lawrence Berkeley National Laboratory (Berkeley Lab). There, I was able to work with the Operations Technology Group by assisting monitor
National Energy Research Scientific Computing Center (NERSC)'s High Performance Systems. I help convert Bash script to Python script for monitoring plugins. I also I worked with Dr. Patricia Ordoñez
as her assistant in Google's Computer Science 4 High School in Puerto Rico in the semester of 2015. Apart from cybersecurity, I'm interested in computer graphics, data visualization and animation. 

My email is <gracemarod@gmail.com>, my Github is
<https://github.com/gracemarod/> and my Linkedln is
<https://pr.linkedin.com/in/gracemarod>.

##Project Descrition:
I'm currently researching in ways to analyze anamolies in IPv6 flow data. In the semester of 2015, we used System for Internet-Level Knowledge (SiLK) tools to acquire IPv4 and IPv6 data. With the data acquired, we were able to make a simple Python script that can take the Destination Port, the IP Source Address and IP Destination Address of all the IPv6 flow data given by the text file made by SILK and create x,y and y coordinates from the range of 0 to 1 to make a 3D cube. This help us see the given data a lot better.
My work is supported by the scholarship
[Academics and Training for the Advancement of Cybersecurity Knowledge in Puerto Rico (ATACK-PR)](http://atackpr.ccom.uprrp.edu/)f
funded by the National Science Foundation under Grant
No. DUE-1438838. 

##Project Goals
This semester I want to concentrate more in using visualization  methods to help us analyze anomalies in IPv6 flows better. So far our goals for this semester are:
- Implement the 3D cube for IPv6 address to be real time.
- Find and use new methods to visualize flow data. 

#Week update

##Week 1 ( 01/25/16 - 01/30/16):
- Complete application's requirement to submit a poster proposal for the Tapia Conference 2016.
- Fork TOA repository and implement IPv6 flow data in the Cube of Doom (cube.py).
- Went to Julio's and Ian's presentation to see their project on visualazing IP flow data.

##Week 2 (01/31/16 - 02/06/16)
- Start reading papers to get more ideas on visualazing IP flow.
- Got a new idea from looking at some projects. After I finish the cube of doom, I want to try and convert the IPv6 adresses to geoIP. With them, using Maxmind database, I want to is display all the ip addresses that connected to the UPR's network wihting a map.   

##Week 3 (02/07/16 - 02/14/16)
- Donwloaded Maxmind's GeoIP of IPv6 cities and countries.
- Went to Cheo's presentation on Friday where he explained how the Cube of Doom visualizes its flow data and 
  the needed fields from a flow so the cube can display them. 

##Week 4 (02/15/16 - 02/21/16)
- Julio send me a json with ipv6 flow data.
- After figuring how a json works in Python scrypt for a whi;e, I was able to display the desired data.
- I want to display all the data in a table format, and be able to have the option to choose the fields you want to display.
