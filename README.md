# in-class-activities
## Devlogs
### W1
Hello world!
### W2
1. The r, g, and b variables are floats because they can be fractional (unlike integers), and they are not text or true/false statements.
2. The bounce variable is an int because a ball cannot bounce a fraction of a time, and it is not text or true/false statements. 
3. I thought the correct option would be r+=0.1f, but it wasn't correct because it was missing a semicolon.
### W3
Table #15
The parameters would be the sanity level (0-100) and the return type would be void. 
1. Classes are like architectural blueprints for buildings because they are templates, while Components are like the buildings made using the blueprints. The characteristics of each building (eg. a house and a school have different purposes, so the features they have differ) are like the Methods, so a house blueprint (Class) will probably have at least one bedroom. Member variables are smaller details on blueprints, such as a client's preferred house color or layout, because they can differ from blueprint to blueprint, even though the general structure (house) is the same.
2. I wasn't able to get to this part of the project, but I would guess that it's because each bounce is changing the color, so when it bounces too many times it runs out of colors to choose from.  
## W4
Table #15
line 17: The boolean member variable states that the player state of being grounded is true (player should be on the ground).
line 28: This if statement checks if the space bar is being inputted and if the player is on the ground.
line 32: if the method detects that the space button is pressed,then the player will jump, so the grounded state will be false.
1. We added Rigidbodies to the cat and ball, since they were the two objects that were moving around. The cat had a Capsule Collider, and the ball had a Sphere Collider. We checked IsTrigger on the goal's Box Collider, since that was the object that indicates whether or not the ball went through and scored a goal.
2. The first time I tested the game, I didn't freeze the rotation for any of the objects, so the cat would go flying if it hit the ball wrong. Fixing it was pretty simple, all I had to do was freeze the X and Z rotation and the cat functioned much more normally. 
## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 