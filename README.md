# Control System Design for Active Bus Suspension System



The ride comfort and handling of an automobile depend on the performance of its suspension system. In this project, I have designed a controller for an active suspension system using pole placement technique that avoids large oscillations and dissipates the oscillations quickly. While modeling the system, the hydraulic actuator and the road profile were included as an input and disturbance respectively. The two approaches used to design a controller are pole placement with feed-forward gain and pole placement with integral controller. Based on the performance evaluation of these two approaches, I recommend using the later to control this system.        

This repository contains the codes I developed to implement the controller design project. 


The followings are the results I got after designing the controller

Feed Forward Controller

![](Figures/with%20feed%20forward%20gain.png)

Feed Forward + Integrator Controller -- Step Input Signal 

![](Figures/integrator%20response.png)

Feed Forward + Integrator Controller -- Square Input Signal 

![](Figures/integrator%20response%20square.png)

Feed Forward + Integrator Controller -- Sinusoidal Input Signal 

![](Figures/sinusoidal%20response%20integral.png)
