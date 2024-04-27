# Projectile Motion of a Rotating Object


## Summary
How would the ration of an object affect its trajectory as it is thrown off a tall building? To answer this question, we will explore how the drag force of an object changes as the reference area changes due to the rotation about a certain axis. We will then determine the trajectory of the object with and without the rotation and compare how they differ in terms of the path taken, where the object lands on the gorund, and the time it takes for the object to complete its journey. 


## Motivation/Background
In classical mechanics, one of the first problems we are taught is projectile motion. We start off in one dimesion, with an object falling only in the y-direction. Then we move on to two dimensions, where the object can move in the x and y direction. With this, we can add other variables, such as initial velocity in both directions and air friction. 

By adding rotation to non-spherical object, the affects of air friction on the object will vary, because the drag force depends on both the reference area and coefficient drag. The reference area of the object will differ at various times of the path. We will need to use a computational approach to calculate the drag force on the object at each moment, which we can then use to calculate the total force on the object. 

[//]: # (explain what is known in this field and why it requires a computational approach)


## Results
For the code, we will be using Newton's equations to determine the force, velocity, and position of the object at a certain point. 

$$\vec{F}_{f} = m\vec{g} - \frac{1}{2} \rho C_d A |v_i| \vec{v_i}$$

$$\vec{v}_f = \vec{v}_i + \frac{\vec{F}_f} {m} \Delta t $$

$$\vec{r}_f = \vec{r}_i + \vec{v}_f \Delta t $$


However, for the rotating object, we need to look into the equation for just the drag force. 

$$\vec{F}_{D} =  \frac{1}{2} \rho C_d A |v_i| \vec{v_i}$$


[//]: # (explain your computation and why)


## Questions
Questions that will be answered for this project

