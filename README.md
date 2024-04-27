# Projectile Motion of a Rotating Object


## Summary
How would the ration of an object affect its trajectory as it is thrown off a tall building? To answer this question, we will explore how the drag force of an object changes as the reference area changes due to the rotation about a certain axis. We will then determine the trajectory of the object with and without the rotation and compare how they differ in terms of the path taken, where the object lands on the gorund, and the time it takes for the object to complete its journey. 


## Motivation/Background
In classical mechanics, one of the first problems we are taught is projectile motion. We start off in one dimesion, with an object falling only in the y-direction. Then we move on to two dimensions, where the object can move in the x and y direction. With this, we can add other variables, such as initial velocity in both directions and air friction. 

By adding rotation to non-spherical object, the affects of air friction on the object will vary, because the drag force depends on both the reference area and coefficient drag. The reference area of the object will differ at various times of the path. We will need to use a computational approach to calculate the drag force on the object at each moment, which we can then use to calculate the total force on the object. 

[//]: # (explain what is known in this field and why it requires a computational approach)


## Results
For the code, we will be using Newton's equations to determine the force, velocity, and position of the object at a certain point. We will use the Euler-Cromer method to compute these variables and plot the trajectory of the object using a for loop that will calculate that information until the object reaches the ground (y=0). 

$$\vec{F}_{f} = m\vec{g} - \frac{1}{2} \rho C_d A |v_i| \vec{v_i}$$

$$\vec{v}_f = \vec{v}_i + \frac{\vec{F}_f} {m} \Delta t $$

$$\vec{r}_f = \vec{r}_i + \vec{v}_f \Delta t $$


For the rotating object, we need to look into the equation for just the drag force. More specifically, how the area and coefficient of drag will be changing. To do this, we have to find a way to relate the reference area to the angle of the normal vector of the object with the velocity. 

$$\vec{F}_{D} =  \frac{1}{2} \rho C_d A |v_i| \vec{v_i}$$


[//]: # (explain your computation and why)


## Questions
Questions that will be answered for this project



## Resources

[Projectile motion of a once rotating object: physical quantities at the point of return](https://www.webofscience.com/wos/woscc/full-record/WOS:000381819000009)

[Effect of Projectile Rotation on High-Velocity Impact Fracture](https://link.springer.com/article/10.1134/S1029959922020035)

[The motion of an arbitrarily rotating spherical projectile and its application to ball games](https://iopscience.iop.org/article/10.1088/0031-8949/88/01/018101/meta)

[A tale of two problem solvers (Average cube shadows)](https://www.youtube.com/watch?app=desktop&v=ltLUadnCyi0)

[The Drag Equation](https://www.grc.nasa.gov/www/k-12/VirtualAero/BottleRocket/airplane/drageq.html#:~:text=The%20drag%20equation%20states%20that,times%20the%20reference%20area%20A)

[Theory and Practice of the Hydrodynamic Redesign of Artificial Hellbender Habitat](https://www.researchgate.net/figure/Drag-coefficients-for-different-shapes-and-dimensions-based-on-Prasuhn-1980_fig6_317690978)

[Aerodynamic Drag Characteristics and Shape Design of a Radar Antenna Used for Airport Ground Traffic Control](https://www.researchgate.net/figure/A-summary-of-measured-drag-coefficients-for-Re-10-000-for-a-circular-cylinder-and_fig12_238065804)






