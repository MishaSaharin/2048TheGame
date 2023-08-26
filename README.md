# 2048TheGame

 to play [2048](https://javarush.com/projects/apps/354197)

2048 is played on a plain 4×4 grid, with numbered tiles that slide when a player moves them using the four arrow keys. The game begins with two tiles already in the grid, having a value of either 2 or 4, and another such tile appears in a random empty space after each turn. Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid. If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided. The resulting tile cannot merge with another tile again in the same move. Higher-scoring tiles emit a soft glow; the largest possible tile is 131,072.
If a move causes three consecutive tiles of the same value to slide together, only the two tiles farthest along the direction of motion will combine. If all four spaces in a row or column are filled with tiles of the same value, a move parallel to that row/column will combine the first two and last two. A scoreboard on the upper-right keeps track of the user's score. The user's score starts at zero, and is increased whenever two tiles combine, by the value of the new tile.
The game is won when a tile with a value of 2048 appears on the board. Players can continue beyond that to reach higher scores. When the player has no legal moves (there are no empty spaces and no adjacent tiles with the same value), the game ends.

Краткие правила таковы: у вас есть поле 4х4, разбитое на квадратные плитки. 
В каждом раунде появляется плитка с номиналом «2» (с вероятностью 90%) или «4» (с вероятностью 10%). 
Все плитки можно перемещать в одну из четырёх сторон, при этом если две плитки одного номинала «налетают» друг на друга, они слипаются и их номинал удваивается. 
Цель — получить плитку номиналом 2048. Игрок проигрывает, если после очередного хода невозможно совершить действие.     
Управление с помощью стрелок и пробела.
