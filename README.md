# MedoraBand
MedoraBand is a smart wearable for  geriatric care.

<h1><b>i) Introduction and problem:</b></h1>
<br>One of the major generational gaps, as seen by people and supported by statistics, is the increasing gap between elderly and the fast paced technology. This not only keeps them at bay from using multiple facilities brought by these ‘modern devices’ to ease life, but also keeps then at the lesser reached side of connectivity, as far as telecommunications are concerned. According to a survey published in India Today and conducted by Norway-based telecom giant Telenor: “94% of people above the age of 50 don't have a mobile phone in India. The findings also show that the percentage of elderly people using mobile phones actively is as low as 2%. Furthermore, senior citizens using mobile-data or smartphone is even lesser as they find it 'complex'.” (Source: http://tiny.cc/srcindiatoday)

<br>This not only highlights the massive gap present, but also raises the issue of non-availability of devices comfortable enough for elderly use.

<br>Specially during these times of pandemic and uncertainty, where the world is confined into a seemingly perpetual virtual state, this technological gap takes a greater toll on not just the elderly, but also their kith and kin –us. With more and more people stuck at different places, with technology and telecommunications the only connect with family and friends, it is becoming increasingly difficult to monitor the health of your elderly loved ones, specially taking into account that they are the most affected demographic in any health threatening event.


<br>Technologies like smart watches, health trackers do exist that offer some level of remote tracking, but they are either too expensive, require pairing with specific mobile phones or are not easy to set up.

<br>To mitigate these problems and provide a holistic, stand alone tracker that lets you track the health status of the elderly at your home remotely, we propose MedoraBand.

<h1><p><b>ii) Proposed solution:</b></p></h1>
MedoraBand aims to provide an easy to use and integrated health tracking for your elderly kith and kin, that lets you stay away from them with peace of mind, without worrying about their health conditions. Using tinyML and a highly customisable hardware, this device can be custom made to suit different geriatric needs, offering both the user and their relatives peace of mind in terms of health tracking. An easy to use, 'no-fuss' interface to reduce technological complexity for our elders, whilst being a complete healthcare monitoring solution that bridges the gap of distance between you and your loved ones, was one of the primary agendas behind Medoraband.

<br>Some intuitive features, as proposed to be implemented on MedoraBand, have been listed below:

<br>a. Small and compact form factor that is non-obtrusive to wear, and easy to use. 
<br>b. Long battery life due to low power consumption and larger battery bank. 
<br>c. 24x7 remote tracking of health conditions of elderly people through a simple UI. 
<br>d. Notification alerts for health conditions/anomaly <br>e. Active motion and fall detection –get to know if the person has fallen down. <br>f. 24x7 temperature monitoring <br>g. tinyML supported to detect anomaly in usual pattern. <br>h. Extremely customizable components –components can be handpicked, if required, and the device can be made as specific to the cause as possible.
![WhatsApp Image 2021-09-17 at 11 45 10 PM](https://user-images.githubusercontent.com/45312302/133859326-f5db819c-801b-46f3-9534-dd66f282e3be.jpeg)

Note: To download design files (Fusion 360), find the design page in the repo or follow the link : [https://a360.co/3kjmVGO]
<h1><p><b>iii) Build, technologies used and working:</b></p></h1>
The wearable consists of a low cost microcontroller –like the Arduino Nano 33 BLE sense, AVR IOT or Raspberry Pi Pico as the “Brain” of the machine. Customizable sensor arrays are housed in a 3D printed and lightweight casing, alongwith the controller board.

Machine learning on edge is deployed locally onto the main board to reduce data usage and accurate results. This aspect lets the device lets it detect any anomalies in health conditions (if the observed values are different from that of normally observed).

A lightweight Li-Po bar is proposed as a power source, and can run the low power wearable for a long period of time.
