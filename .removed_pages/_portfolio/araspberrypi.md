---
title: "Raspberry Pi Monitor"
excerpt: "The main ideal behind this project was to have a Raspberry Pi monitor the temperature of our plants."
collection: portfolio
---

### Overview:
The main ideal behind this project was to have a Raspberry Pi monitor the temperature of our plants. Then display that information on a website, so it can be easily accessed. Temperature monitors were hooked up to the Raspberry Pis and placed in the plants. That data is stored in a database and then displayed on the dashboard.


### Results:
The Raspberry Pi will periodically collect the data and will send it to our main computer, which is one of the 2 Raspberry Pis. It has the ability to record data from 2 different Raspberry Pi locations, so the data is collected from both and rendered as a website that is hosted on one of the 2 Raspberry Pis.

<br/><img src='/images/dashboard.png' alt="Pi Dashboard">

The ReactJS frontend has a dashboard homepage showing the most recent temperature and humidity readings from all locations. There is also an information page that displays a line chart that shows the humidity and temperature readings over time. This page also allows for the manual addition and manipulation of the data. The webpage also contains a page that displays the current plants and their information (name of plant, humidity, and temperature ranges).



<br/><img src='/images/piGraph.png' alt="Pi Graph">