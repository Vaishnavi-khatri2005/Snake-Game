# Snake-Game
A simple and fun browser-based Snake Game built using HTML, CSS, and JavaScript.
Control the snake, eat the food, grow longer, and try to achieve the highest score before hitting the wall or yourself.
<br>🎮 Gameplay</br>
Use Arrow Keys to move the snake.
Eat the red food to grow.
Game ends if the snake:
Hits the wall
Collides with its own body
<br>🛠 Technologies Used</br>
HTML5 ,CSS3,JavaScript (Vanilla JS) 
HTML Canvas API – rendering snake and food
<br>🧠 Game Logic / Model</br>
The game works on a grid-based movement model:
Snake position stored as an array of blocks.
Every frame:
New head added in the current direction.
Tail removed unless food is eaten.
Collision detection checks:
Wall boundaries
Self intersection
Score increases whenever food is eaten.

