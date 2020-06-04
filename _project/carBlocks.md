---
layout: project_single
title:  "Car Blocks"
slug: "carBlocks"
---

# Competition

The __Tsinghua-Santander World Challenges of 21st Century Programe__ is a world-wide competition issued by Tsinghua University as a means of motivating research and development among the younger generation to fix the problems of tomorrow. The 2018 edition in which I enrolled with a group of friends was about sustainability. The program consisted of two phases. The initial one, in which candidates could submit their ideas and reports for evaluation, and the final which occurred for two weeks during the Summer on the campus of Tsinghua University in Beijing China. 

Me and a group of 3 other friends, all engineering students, developed a project, __Car Blocks__ based on the idea of modular electrical vehicles with the hope of addressing the current problems of the car industry. Our project was recognized as one the best submitted and therefore we were invited to participate in the finals.  

We were then given materials to develop a miniature prototype of our idea while also attending several lectures about product development and entrepreneurship. For the construction, we required to master several areas of expertise such as Computer-Aided design, 3D printing, Arduino programming, and electronics. We also got to experience life in China in the most prestigious university in the country while also meeting entrepreneus from all over the world which was an extremely interesting experience. It's also worth mentioning that on average we were the youngest team in the finals. At the time all of us were in the third year of our bachelor's. 

In the end, we got to present our project to local professors and investors to be evaluated. The initial report that was submitted by the end of phase 1 can be read below. 


<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/tsinghuaGang.jpg">
  <p align="center">The entire group of participants and organizers in the Summer Palace, Beijing, China.</p>
</p>


# Report
									
<p style="text-align: center;"><i>Innovation makes the world better – urban sustainability</i></p>

### Authors

- André Cavalheiro @ Instituto Superior Tecnico
- Henrique Amaral @ Intituto Politécnico Leiria
- Miguel Lino @ Insituto Superior Tecnico
- Ricardo Araújo @ Faculdade de Ciências e Tecnologia


## Abstract

Today there are serious problems in transportation, particularly in motor vehicles. In this project, with the hopes of trying to solve some of these problems we propose a new kind of vehicle that is optimized to meet the individual needs of each user regardless of his situation. This is done by introducing a new mechanism that would enable the creation of modular electric vehicles.  In this report, we explain the technical principles behind this mechanism as well as an overview of the current state of the market of electric cars to justify the need for such a product.


## Content

- Introduction
   - General automotive Information
   - Problem description and explanation
- Goals and objectives
- Project initial Approach
- General research
- Battery Analyses
- Chassis and Dynamics
   - Materials research
   - General Safety considerations
- Vehicle System Internal Communication
- Prototyping
   - Module locking device
- Conclusions
- References



## General Automotive Information

With an exponential growth in technology, there is a growing need for mobility. Focusing our analysis on cars is noteworthy that is one of the most widely use mean of transportation. As shown in figure 1 the number of cars has gradually increased over time. Nowadays the growth has been more relevant in Asia.
This trend can also be analysed by the number of vehicles per thousand habitants chart shown in figure 2 and also be related with cars per household.

<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig1.png">
  <p align="center">Figure 1 – World vehicles in Operation [1]</p>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig2.png">
  <p align="center">Figure 2 – Global Analyses-Vehicles Per 1000 People [3] </p>
</p>


## Problem Description

With this growth in the number of vehicles the space of use begins to be small which leads to large traffic jams as well as overcrowded car parks. The average number of people in a given vehicle has been decreasing (visible in figure-3) which contributes negatively to the two points mentioned above.
Another very serious problem with the increase in car usage is the emission of pollutants into the atmosphere. Only recently less dependent alternatives on fossil fuels have been used because these greener alternatives have always been discouraged by several oil corporations.
At last, but not least is the problem of cars having a fixed purpose. A different vehicle is mandatory, one that is able to adapt to the different needs of a person. In other words, an individual or company that needs to transport goods has to have a truck with a powerful engine (that spends more fuel). Logically this ceases to make sense if the usage of the vehicle turns to personal use for example go to work (needing a smaller and economical car). This problem leads many people to acquire more than one vehicle because it ends up compensating in terms of fuel costa and car parking.


<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig3.png">
  <p align="center">Figure 3 – Percentage of seat occupancy through time [4] </p>
</p>




## Goals and Objectives

This project aims to solve the problems identified below:

- reducing CO2 emissions through the creation of a vehicle that is not dependent on fossil fuels;
- Improve the occupancy rate of vehicles;
- Make a vehicle more versatile, eliminating the need for a household, company or single person to have more than one vehicle.


The resolution of these points allows a better urban sustainability in private transportation.


## Initial Approach

The idea of this project emerges as a solution to combat most problems related to this type of mobility.
Our concept is based on the creation of an automobile vehicle consisting of two modules. These combinations can be a two-seat utility vehicle, a light freight vehicle and a familiar vehicle with a capacity of 5 seats.


<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig4a.png">
</p>



The concept becomes even more interesting with the use of electric motors instead of internal combustion engines because in addition to all the ecological advantages we can improve individual characteristics of the modules. In other words, not only will the base module be equipped with one or two electric motors (or one hybrid motor) plus the respective batteries, the other modules will be equipped with their own set of batteries and electric motors according to their needs. This allows for a more dynamic usage of power according to the user's needs.
Finally, it should be noted that the customer does not need to purchase all the modules at once. The only required module is the base module. From then on out it's the customer's decision which modules to acquire according to their own needs.


<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig4-7.png">
</p>


## Research

Electric cars are getting more popular as time goes by, and with that comes a lot of benefits. Electric infrastructure will improve people’s lives. If they become as wide spread (or even more, because of their simplicity) as fuel pumps, it would exponential grow the numbers users of electric cars. Studies say that the average buyer of electric cars are middle aged man with higher education. According to OPEC electric vehicle forecast the market growing expectations is rising exponentially as shown in figure 8.





## Battery Analyses

When choosing a battery type, one of the most important things to consider is the type of battery. There are 4 main types of technology’s that are used in the most used energy storing devices: Lead acid, Nickel–metal hydride(NiMH), Lithium-ion(LIB) and Lithium polymer(Li-Po).
When starting to analyse these types of batteries we can almost start by discarding lead acid. It is true that lead acid batteries have been used in cars for many years, however not for the purpose we will be using them. Lead acids have a lot going for them. They are the safest, they are the ones who need the least complicated circuit for charging and for the most part they are cheap. However, size and weight is something we have to consider and their energy density which compared to the other technology’s it falls behind:

<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig8.png">
    <p align="center">Figure 8 – Electric Propulsion Vehicle market growing expectations [2]</p>
</p>

Now when comparing the other three technologies it gets a little more complicated. It’s easy to jump to the conclusion that Lithium-ion is the best choice (it’s what Tesla uses, and they know what they are doing) and that’s the conclusion we will reach to. But Why?

First, for a car we need the most energy possible (more energy = more Kilometres) so we can discard Nickel–metal hydride as Lithium-ion and Lithium polymer are the most energy dense of all them. So why not use Lithium polymer? We have seen that its energy density its almost the same as Lithium-ion, they have the same problems with charging (over-charging, under-charging, over-heating, instability when ruptured) so what is the difference? Well Li-Po have the peculiarity that they can bend and that can be seen as good and bad. It would grant a level of security however bend them too much and they will rupture and combust. 

Another thing that we have to take in consideration when using li-Po’s in a big package is that they will expand in case of over charge (due to slight vaporization of the electrolyte), and that would be catastrophic. So even Lithium-ion are not the perfect choice (they need to be cooled by a refrigerating system, there charging circuit is complicated and they are one of the most expensive technology’s) they are the right type for this project.


## Chassis and Dynamics

### Materials research

The chassis of a vehicle is the structure where all the parts will be integrated. It is
responsible for the rigidity of the car and also guarantees the safety of the passengers.

Since we are aiming for a type of car that is built on modules so that it’s cheaper for the user to buy one of our cars instead of buying multiple cars for diverse purposes, the type of chassis used in our vehicle would be a unibody aluminium chassis for each module.
This would lower the manufacturing price of the car, making it cheaper for the final user, on the opposite of more expensive chassis and materials types, like for example a carbon fiber monocoque. One more reason for this type of chassis is the ability to unite two or more modules with the auxiliary of the chassis, i.e. the system that brings the modules together must be integrated with the chassis of each module so that we are able to guarantee a more sustainable union between modules and also to give more rigidity to the whole assembly.

### General Safety considerations

In terms of safety, our module car would have an integrated collision avoidance system to avoid accidents with pedestrians. The technology is based on radar with the auxiliary of lasers and cameras that would detect a person in front of the car and it would automatically activate the brakes if the car is going in the direction of the pedestrian. The same would go for any other object like walls or other cars, if the driver doesn’t make a change of course or brakes until a certain moment when it is critical to take action to avoid a collision, then the system will do that on it’s one.

On the structural safety side, the most critical aspect of it is the fact that the module car has to be built of 2 or more separated parts, which is not ideal in terms of the rigidity of the chassis. Our solution for this problem is to make the locking mechanism of the modules a part of the aluminium chassis. This can be achieved by making the external chassis part (the part which is going to mount on the other modules) with several inlay beams that will be part of the locking mechanism, giving it the necessary torsional rigidity and overall integrity of the set of modules.


## Vehicle System Internal Communication

One of the most important parts of every electric car is its Eletric controller. Its function is to take the required power from the batteries to the motors according to what it is required at each instant. During this process the direct current from the batteries it's transformed into alternating current which is then used in the AC motors. 
In this project we not only have several batteries and motors, but the amount of them depends on which modules we are using. For those reasons this makes the controller a lot more complex than usual. For a system like this to work there are some big aspects that we need to watch out:

First of all, there needs to be multiple controllers and multiple motors. Each of them responsible for a specific part of the system (that part being the module which they belong to). Why? Well if our goal is to have dynamic vehicle which adapts itself to the needs of the user, then the amount of power usage must also adapt. Each module must be responsible for its own power consumption and therefore must have its own motors and batteries.

There are a few ways to do this. One of them is to have a single motor per wheel. Although this is not the very common amongst today's commercial electric vehicles it is a certainly possible and common amongst electric race cars. An alternative would be to have a single motor for each pair of wheels which already exist in the market for example Nissan Leaf.


<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig9.png">
  <p align="center">Figure 9 – Electric Propulsion Vehicle with a single electric engine [2]</p>
</p>

However, it would be very complex, and not very efficient for a single controller to interact directly with every motor. Which leads us to the other important detail we need to take into consideration: Each module needs to have its own controller which would control the module's motors according to the inputs deriving from the main controller located in module zero.

Due to the complex nature of the controller system there would have to be some type of configuration between the module installation and usage. Such as a _Select_ option on the vehicle's cockpit in which the user would be able to select which module is in usage. The main controller would then verify if each sub-controller is responding accordingly and set its own configurations to work as needed.

## Prototyping

### Module locking device

This is undoubtedly the most complicated component to be developed. It is worth noting the importance of it in the safety and dynamics of the vehicle because it is where the coupling of the two modules takes place.
The overall idea of this part will be the use of a set of fitting parts that are part of one module and then joined through locking systems powered by electric actuators. It is also very important for the assembly to remain locked even in case of power failure of the actuators.

<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig10.png">
  <p align="center">Figure 10 – Module Locking Device</p>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig11.png">
  <p align="center">Figure 11 – Module Locking Device</p>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig12.png">
  <p align="center">Figure 12 – Module Locking Device</p>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/andre-cavalheiro/andre-cavalheiro.github.io/master/static/projects/carBlocks/fig13.png">
  <p align="center">Figure 13 – Electronic Linear Actuator</p>
</p>


## Conclusions

In conclusion it should be noted that it is important to optimize the means of transportation so that they have a less impact on the environment, more versatile and user friendly.
Regarding the initial ideas of this project we can highlight that this is quite possible to be accomplished, but that clearly needs much more research, dimensioning/design and simulations related to integrity of the chassis and modulo locking device in order to make the project practicable and approved by the laws imposed.


## References

[1] http://wardsauto.com/site-files/wardsauto.com/files/imagecache/large_img/uploads/2017/10/world-vio-2010-2016.png

[2] https://dqbasmyouzti2.cloudfront.net/assets/content/cache/made/content/images/articles/Electric_Vehicle_Forecast_XL_2054_1086_80.jpg

[3] https://www.energy.gov/eere/vehicles/fact-841-october-6-2014-vehicles-thousand-people-us-vs-other-world-regions

[4] https://www.eea.europa.eu/data-and-maps/indicators/occupancy-rates-of-passenger-vehicles/occupancy-rates-of-passenger-vehicles

[5] http://eie.uonbi.ac.ke/sites/default/files/cae/engineering/eie/A%20MICROCONTROLLER%20BASED%20POWER%20CONTROLLER%20FOR%20ELECTRIC%20VEHICLE.pdf

[6] https://www.design-engineering.com/wp-content/uploads/2016/02/16-Feb-THO-linear-actuator-625.jpg

[7] https://www.goauto.com.au/assets/contents/c02ba9edcfdfddfd14d346533d663ee377a1df1.jpg
