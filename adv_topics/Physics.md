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
    - Explain the player (lil man)'s movement on the ground (friction) and in the air (air resistance). 
    - Importance of friction to add realism
    - After releasing the movement key on the ground, the user will slow to a stop, rather than just stopping at the blink of an eye. 
    - Show air resistance when gliding and on acorn
  - Math used
    - Explain the equations of motion with air resistance
      - where m is the player’s mass, g is the gravitational acceleration, b is the drag coefficient. Both a and v can be represented as differentials 
  - Implementation of friction in game
    - Explain Euler numerical integrator to solve the differential equations of motion

- Topic 2 (~10 minutes)
  - Introduction to conecept
    - Exploding acorn that ejects some harmful particles to the player 
  - Math used
    - Simple case of the conservation of momentum
      - with initial conditions dependent on the velocity vector of the explosive acorn before explosion
    - Basic derivation, each particle resulting from the explosion shall be treated as a projectile
  - Implementation of explosion particles in game
    - Follow the aforementioned equations of motion for projectile motion with an initial velocity vector. 
    - Few particles that can actually damage the player 
    - Will be ejected out from the center of our explosion, subject to projectile motion.

- Topic 3 (~20 minutes)
  - Introduction to concept
    - Used for the water/lava in our game
    - Creating a “fluids” simulation by treating player as a simple harmonic oscillator moving across space
    - Triggered by an initial collision with a water tile and will end when player is no longer colliding with water 
    - Ideally, momentum in horizontal and vertical directions are conserved
  - Math
    - Will go through brief derivation of damped oscillation equation in slides
    - Need to decide on what case of damped harmonic motion we will consider (critically damped, underdamped, overdamped) 
    - Overdamped makes the most sense considering how we are picturing motion through water
    - Use Euler Cromer method to implement by calculating time steps
    - Walk through steps of the algorithm in slides

...


## Presentation III

- Topic 1 (XX minutes)
  - ...
- Topic 2 (XX minutes)
  - ...
- Topic 3 (XX minutes)
  - ...
...
