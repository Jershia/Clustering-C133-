# Clustering
* *We plotted different charts in this class*
* *We learned about the Goldilock zone of a planet.*
* *We calculated the speed of all the planets.*

## Steps To Find suitable planets For Survival
  * *Look at the columns orbital_radius and orbital_period:*
     * *Orbital Radius - It is the distance of the planet from the host star.*
     * *Orbital Period - It is the time the planet takes to complete one orbit around its sun.*
  * *We convert the Years unit to Days for Orbital Period (by multiplying it with 365)*
  * *We remove the rows that have unknown values in these columns.*
  * *We plot the chart after converting Years and Days to Days in Float and we also remove the keyword AU from the 9th Column (element on index 8). We are then plotting a scatter plot for the same.* 
  * *The list of suitable planets gives us 696 and out of those, only 25 are in Goldilock Zone! That’s how rare it is! We are really lucky to have Earth!*
  * *We know the time it takes and we also know the radius of the orbit. Using the formula to find the circumference of a circle, we can find out the distance and the
speed of the planet!*
  * *Given this data, we can assume that if a planet revolves at the speed of 200km/s, we can survive that.*
  * *Also, make sure that we have the orbital_period in days. We need to convert it into seconds because we want to calculate the speed of the planet in km/s which is
kilometers per second, instead of kilometers per day.We also need to convert our orbital radius from AU to KM*
  * *Filter out the planets that have speed more than 200km/s.*
  * *We find out that there are only 8 planets who can support us in terms of speed.*
 
## Code is given below
* https://colab.research.google.com/drive/1wm3ocsV09akjXuumDtjHVv3Eu-WGBeJn

## Facts :
* *AU is short for Astronomical Unit which is roughly the distance between the Sun and the Earth.**1 AU = 1.496e+8**.*
* *Goldilock Zone is the habitable zone where the planet is more likely to have just the right conditions to sustain life.For us, we are at the very beginning of the Goldilock Zone whereas Mars is at the end.*
* *Earth is 1AU from the Sun and Mars is 1.5AU from the Sun.*
* *Any planet that lies within 0.38 - 2 AU is likely to be habitable.*
* *Earth travels at the speed of 30km/s when revolving around the moon.*
* *Speed = Distance/Time*
* *Circumference of a circle = 2πr*
* *Our Earth revolves around the sun at 30km/s. Similarly, our solar system revolves around the center of the Milky Way galaxy at the speed of 200km/s.*
* *.**1 Day = 86400 Seconds**.*
* *.**1 AU = 1.496e+8**.*
