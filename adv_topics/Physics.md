# Physics Advanced Topic Presentations

Before your presentation, use this file to get your talk outline approved. Be
sure to provide an estimated time to spend on teach topic (totalling 45 minutes)
and be sure not to repeat any topics covered in previous presentations.

## Presentation I
## Cats with Bats (slugout)

- Topic 1 Ball Properties and Dynamics (20 minutes):
  - different properties of the balls, including size, weight, elasticity, and density.
  - how they influence the behavior of the balls when they collide with each other and with other game objects.
  - ball spinning and its effect on gameplay (bat hits ball or ball hits object), including strategies for players to use spinning to their advantage.
- Topic 2 Collision Detection and Resolution (15 minutes)
  - Point of contact for circles
  - multiple objects colliding
  - Explain how you handle collision resolution, including bouncing off walls and surfaces, and how it affects gameplay.
  - optimizing collision detection for performance in a real-time game.
- Topic 3 Friction and Energy Absorption (10 minutes)
  -  friction in physics and how it affects the movement of balls on different surfaces.
  - Explain how we implement varying levels of friction and energy absorption for different materials and surfaces in the game
  - impact of friction on gameplay, such as how it affects ball speed and player movement.


## Presentation II

- Topic 1 (~15 minutes)
  - Introduction to concepts
    - The player (lil man) will experience friction based physics. This involves his movement on the ground (friction) and in the air (air resistance). 
    - This way, the game will look more realistic. 
    - After releasing the movement key on the ground, the user will slow to a stop, rather than just stopping at the blink of an eye. 
    - When gliding, lil man will be subject to air resistance. When thrown, the acorn will also be subject to air resistance through projectile motion.
  - Math used
    - The equations of motion with air resistance are as follows (courtesy of https://physics.csuchico.edu/kagan/204A/lecturenotes/Section15.pdf):
    where m is the player’s mass, g is the gravitational acceleration, b is the drag coefficient. Both a and v can be represented as differentials 
  - Implementation of friction in game
    - To implement this, it would be sufficient to use an Euler numerical integrator to solve the differential equations of motion. (http://www.physics.umd.edu/hep/drew/numerical_integration.html#Euler)

- Topic 2 (~10 minutes)
  - Introduction to conecept
    - Want to have an exploding acorn that ejects some harmful particles to the player. 
  - Math used
    - This would just be a simple case of the conservation of momentum (with initial conditions dependent on the velocity vector of the explosive acorn before explosion). 
    - This is a pretty straightforward and easy to understand derivation. Each particle resulting from the explosion shall be treated as a projectile.
  - Implementation of explosion particles in game
    - All we need to do in this case is to follow the aforementioned equations of motion for projectile motion with an initial velocity vector. 
    - There will be a few particles that can actually damage the player. 
    - These will be ejected out from the center of our explosion and will be subject to projectile motion.

- Topic 3 (~20 minutes)
  - Introduction to concept
    - Use mostly for water. Creating a “fluids” simulation by treating player as a simple harmonic oscillator moving across space. 
    Will be triggered by an initial collision with a water tile and will end when player is no longer colliding with water. Ideally, momentum in horizontal and vertical directions are conserved.
  - Math
    - Will go through brief derivation of damped oscillation equation in slides.
    - Need to decide on what case of damped harmonic motion we will consider (critically damped, underdamped, overdamped). 
    - Overdamped makes the most sense considering how we are picturing motion through water.
    - Use Euler Cromer method to implement by calculating time steps
    - Walk through steps of the algorithm in slides (http://www.physics.umd.edu/hep/drew/numerical_integration.html#EulerCrome)

...


## Presentation III

- Topic 1 (XX minutes)
  - ...
- Topic 2 (XX minutes)
  - ...
- Topic 3 (XX minutes)
  - ...
...
