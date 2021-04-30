---
layout: post
title: Air Quality report within the campus of TIET
date: 2020-08-09 01:00 +0530
modified: 2020-08-09 16:49:47 +05:30
description: A brief report on the management and analysis of the air quality within the campus of the Thapar University
tag:
  - pollution
  - arduino
  - aqi
---
  # Thapar Air Quality

**(A brief report on the management and analysis of the air quality
within the campus of the Thapar University)**


## Table of Contents

1. Introduction
2. Theory
3. Working & Observations
4. Technical Outline
5. Conclusion
6. References


## Introduction

Recent global trends in socioeconomic inequalities and rise in pollution levels, paired with
the lack of awareness and the lack of self-regulation regarding an individual’s exposure to
pollutant levels in his/her immediate surroundings have come up as serious problems that
do not have any success or successfully implemented solutions yet.​The plethora of
harmful health effects associated with high concentrations of air pollutants has made it
increasingly important for citizens to know about and engage with these concentrations in
the air around them in real-time.
In Thapar University itself, various problems among the students and faculty were observed
due to increased Air Pollution levels within the campus caused by regional-scale processes.
We, in this environment project, tried to collect dust density and gas composition data over
a period to observe different reasons due to which the pollution level increment can be
explained. The data is observed in different places (Boys Hostel C and Girls Hostel G) and
taken multiple times during the day to provide an accurate representation. We also used
Internet Of Things (IoT) as an aid for our purpose by getting the readings over the Internet
by using Firebase and showing real-time data.


## Theory

**Air pollution**


Air pollution occurs when harmful or excessive quantities of substances including gases
(such as carbon dioxide, carbon monoxide, sulphur dioxide, nitrous oxides, methane and
chlorofluorocarbons), particulates (both organic and inorganic), and biological molecules
are introduced into Earth's atmosphere. It may cause diseases, allergies and even death to
humans; it may also cause harm to other living organisms such as animals and food crops
and may damage the natural or built environment. Both human activity and natural
processes can generate air pollution.

**Air Quality In India**


India is home to 15 of the 20 most polluted cities in the world with some studies indicating
nearly 700 million Indians are exposed to unhealthy air.

In 2016, a World Health Organisation (WHO) study found that fourteen of the twenty
world’s most polluted cities belonged to India. Kanpur, in Uttar Pradesh, emerged as the
city with the highest PM2.5 level, standing at 173 (17 times higher than the limit set for
safety). It is estimated that in 2016, over 9 lakh deaths were caused due to air pollution in
India. Some other cities with high PM 2.5 levels include Faridabad, Varanasi, Gaya, Patna,
Delhi, Lucknow and Agra. Delhi, as the capital of the country, too gained a notorious
reputation as a result of its severely poor air quality. In the past, there have been multiple
instances where the presence of heavy smog in the national capital has led to the
declaration of public health emergencies, flight cancellations, school closures and
inevitable political acrimony.

The sources of air pollution are multiple. Vehicular emissions, crop burning, generation of
dust- particularly from construction sites, depleting tree cover and poor waste management - all contribute towards the declining air quality. One of the problems with tackling air
pollution solely at the city level is that several factors which contribute towards increasing
pollution levels have their origins in the bordering suburban areas. In Delhi, for instance,
one of the major factors responsible for its declining air quality is paddy straw burning in
its neighbouring states.

**Vehicular emissions, crop burning, generation of dust- particularly from the construction
sites, depleting tree cover and poor waste management – all contribute towards the
declining air quality** ​.

**AIR quality in Punjab and Haryana**


An AQI between 0-50 is considered "good", 51-100 "satisfactory", 101-200 "moderate",
201-300 "poor", 301-400 "very poor", and 401-500 "severe". Above 500 is "severe-plus or
emergency" category.

The cities of Hisar and Bhiwani in Haryana report their worst air quality as their AQIs
stood at 470 each (severe category), as per the data provided by the Central Pollution
Control Board (CPCB).
Among other Haryana districts, Faridabad (AQI 449), Gurugram (446), Jind (445),
Fatehabad (430), Sirsa (415), Rohtak (412) and Panipat (408) also recorded their air quality
in the "severe" category
Punjab witnessed air quality in "very poor" and "poor" categories. Amritsar's AQI was 362,
followed by Bathinda (333), Patiala (285) and Jalandhar (276),. the CPCB data said.

AQI in the Union Territory of Chandigarh was recorded at 242 which is considered as
"poor".


On November 11 and 12, 794 and 529 incidents of farm fires were reported in Punjab, with
Sangrur recording maximum cases, bringing the total no. Of stubble-burning incidents to
more than 48,000 so far in the state.
Haryana reported a total of 6,099 incidents of farm fires in this season so far.

**Meteorological factors within India**


The data for the project was obtained from the website of the Central Pollution Control Board
(CPCB). Currently, CPCB tracks the Air Pollution levels across 23 dimensions (variables).
Day wise, hour wise (for some variables). Data is available online across the following
dimensions:


- Nitric Oxide (NO)
- Carbon Monoxide(CO)
- Suspended Particulate Matter/RPM/PM
- Nitrogen Dioxide (No2)
- Ozone
- Sulphur Dioxide (SO2)
- PM 2.5 (DUST 5)
- Oxides of Nitrogen (Nox)
- PM10 DUST
- PM10 RSPM
- Solar Radiation

India’s Central Pollution Control Board now routinely monitors four air pollutants namely
Sulphur dioxide (SO2), oxides of nitrogen (NOx), suspended particulate matter (SPM) and
respirable particulate matter (PM10) & (PM 2.5). These are target air pollutants for regular 
monitoring at 308 operating stations in 115 cities/towns in 25 states and 4 Union Territories
of India.

The monitoring of meteorological parameters such as wind speed and direction, relative
humidity and temperature has also been integrated with the monitoring of air quality. The
monitoring of these pollutants is carried out for 24 hours (4-hourly sampling for gaseous
pollutants and 8-hourly sampling for particulate matter) with a frequency of twice a week,
to yield 104 observations in a year.


- Data includes odd-even pilot project (phase I & II) for 4
- The data covers 15 days prior to the pilot and the 15 days of the
- Data on a social conversation that took place around the odd-even experiment (phase II). Primarily twitter.

**Stubble Burning**
Stubble burning is intentionally setting fire to the straw stubble that remains after grains,
like paddy, wheat, etc. have been harvested.
There are other methods like removing crop by use of machines like happy seeder that
shreds the crop residues into small pieces and uniformly spread them across the field but it
fails to be cost-effective.
Stubble burning results in the loss of nutrients and farmers have to spend on chemical
fertilisers to maintain soil quality.
The smoke released also causes pollution which can affect a larger area and have serious
health impacts. The floating threads of conducting waste also cause damage to electrical and
electronic equipment.
The risk of fires spreading out of control is also there while this method of Burning leads to
the ground temperature rising and the soil drying up, necessitating additional water for


irrigation. Livestock, too, is impacted by crop burning. It has been found that milk
production falls up to 50% during the two months.

Air pollution sensors are devices that monitor the presence of air pollution in the
surrounding area. They can be used for both indoor and outdoor environments. For
research, the pollution sensors had been placed at two places on campus, G Hostel and C
Hostel. It was decided that on Monday, the sensors will detect pollution levels in G Hostel
from 6:30 am to 7:30 am and in C Hostel from 6:30 pm to 7:30 pm and on the next day,
vice versa would take place. This method was followed for the entire weeks. These
observations were taken from 6th October to 19th October, which was a week before
Diwali and from 3rd November to 10th November, a week after Diwali. This timeline had
been chosen, to observe the change in pollution before and after Diwali and stubble burning
season.


## Working & Observations

The hardware side of the project will be comprised of the following components (individual
details explained in the later sections) :
- NodeMCU
- Dust Sensor
- MQ-135 Sensor
NodeMCU will act as a microcontroller for the system. Once turned on, readings will be
taken at an interval of 5 minutes as it takes 5 minutes for both the sensor to initialize and
get ready to take readings. The readings will be taken simultaneously and will be stored.
The final reading will be calculated as an average of all the readings in that hour and will
further be used. It will be sent over the internet to a firebase Database server where it will
be stored. These values can be accessed anytime using the Flutter based mobile
application(details in the next section).

The data observed over the period is given at:

![image](https://i.imgur.com/ODTDsMY.png)
![image](https://i.imgur.com/l4V5oTG.png)
![image](https://i.imgur.com/YN9RS1I.png)



## Technical Outline

**Dust Sensor**


The Sharp GP2Y1010AU0F is an inexpensive and compact dust sensor that works by
making use of an optical sensing system. This sensor utilises an IR emitting diode in
combination with a light-sensitive transistor and uses them to sense the light reflected by
dust particles suspended in the air. The sensor is highly effective in detecting extremely
fine particles like those present in cigarette smoke. It can also effectively distinguish house
dust from smoke particles by observing the pulse pattern of the output voltage obtained.

Specifications:
● Operates under 20mA, won’t be wasting the smartphone’s battery.
● Operating voltage:4.5-5.5V
● The presence of dust can be detected by the photometry of only one pulse
● Dimensions: 46.0 x 30.0 x 17.6mm

**NodeMCU**

NodeMCU is an open-source LUA based firmware developed for the ESP8266 wifi chip. By
exploring functionality with ESP8266 chip, NodeMCU firmware comes with ESP
Development board/kit i.e. NodeMCU Development board.​ NodeMCU Dev Kit has
Arduino
like Analog (i.e. A0) and Digital (D0-D8) pins on its board.​ NodeMCU provides access to
the GPIO (General Purpose Input/Output) and a pin mapping table is part of the API
documentation.​It supports serial communication protocols i.e. UART, SPI, I2C etc.


**MQ135**

The MQ series of gas sensors utilize a small heater inside with an electrochemical
sensor​. The MQ135 gas sensor has high sensitivity in ammonia, sulfide, smoke and in other
harm full gas. It is low cost and suitable for different applications. The MQ-135 gas sensor
senses the gases like ammonia nitrogen, oxygen, alcohols, aromatic compounds, sulfide and
smoke. The boost converter of the chip MQ-3 gas sensor is PT1301. The operating voltage
of this gas sensor is from 2.5V to 5.0V. The MQ-3 gas sensor has a lower conductivity to
clean the air as a gas sensing material. In the atmosphere, we can find polluting gases, but
the conductivity of gas sensor increases as the concentration of polluting gas increases.
MQ-135 gas sensor can be implemented to detect smoke, benzene, steam and other
harmful gases. It has the potential to detect different harmful gases. The MQ-135 gas sensor is
low cost to purchase. The basic image of the MQ-135 sensor is shown in the below figure.

**Android App**


Flutter is a framework developed by Google for making android apps. The app uses flutter
as the front end and dart as its backend language. The data is stored in firebase(cloud service)
from where it fetches and displays it in a human-readable way. It shows daily average dust
density and air quality levels, previous days day and night dust density and air quality
levels.



## Conclusion

With all the data collected multiple observations had been made, some of them includes:
● Dust Density, Pollution level and Gas Composition is noted to be relatively
higher in the morning as compared to evening. During the night, cold air
settles closer to the ground due to the lack of heating from the sun. This
stagnant air is a breeding ground for pollutants to accumulate, which is why
we typically see more pollution at night and during the early morning hours.
● A major increment in pollutants were shown after the Diwali Break. Reasons
for this was the stubble burning season and extremely dangerous pollution
levels were observed on 3rd November. But also just after two days there
was a decrease in the pollution level which can be explained with the
sunlight, another contributing factor.
● CO2 levels and other harmful gases level did not change over a longer
period of time. Further conclusions can be made about how the pollutants
do not affect the concentration of these gases.


## References

_1. Monitoring air quality:_ ​ _[http://www.howmuchsnow.com/arduino/airquality/](http://www.howmuchsnow.com/arduino/airquality/)
2. https://www.allaboutcircuits.com/projects/communicate-with-your-arduino-through_
    _-android/
3. Measurement of PM2.5 Concentrations in Indoor Air Using Low-Cost Sensors and_
    _Arduino Platforms_ ​ _https://www.ama-science.org/proceedings/getFile/ZwD2BD==
4. World Health Organization
5. World Health Organization, Media Centre (2016). Air pollution levels rising in_
    _many of the world’s poorest cities._
    _[http://www.who.int/mediacentre/news/releases/2016/air-pollution-rising](http://www.who.int/mediacentre/news/releases/2016/air-pollution-rising)
6. https://doi.org/10.1155/2017/
7. Apte et al., Environmental Science and Technology. Addressing globalmortality_
    _from ambient PM2.5 (
8. GP2Y1010AU0F-KG017 Dust Sensor datasheet_ ​ _:_
    _https://www.sparkfun.com/datasheets/Sensors/gp2y1010au_e.pdf
9. Chauvenet, William. A Manual of Spherical and Practical Astronomy V. II. 1863._
    _Reprint of 1891. 5th ed. Dover, N.Y.: 1960. pp. 474–566._


