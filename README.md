Frozen Lake is a game environment where the goal is to navigate from a starting point to a goal point on a frozen lake without falling into any holes. The lake is composed of different tiles, some of which are frozen and others that are holes. The player controls an agent that can move up, down, left, or right on the lake.

Game Rules

The game starts with the agent at a designated starting point.
The agent can move in one of four directions: up, down, left, or right.
The agent's movement is not always guaranteed, as the tiles can be slippery, causing the agent to move to a random neighboring tile instead of the intended direction.
The game ends when the agent reaches the goal point or falls into a hole.
Game Layout

The game layout is a 2D grid, with each tile representing a different location on the lake.
The layout includes the following types of tiles:
Frozen tiles (F): safe to move on
Holes (H): avoid these tiles, as they will end the game
Start tile (S): the agent's starting point
Goal tile (G): the agent's destination
The agent starts at the top-left corner (S) and must navigate to the bottom-right corner (G) without falling into any holes (H). The frozen tiles (F) are safe to move on, but the agent must be careful not to slip and fall into a hole.
