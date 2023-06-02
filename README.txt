Desciption of the task:

A simple game-like interface where a baby shark finds its way through obstacles and navigates
automatically to capture fish placed by the user. A small AI engine needs to be implemented
that determines what is the best action for the shark to take, to avoid obstacles and maximise
the number of fish.

The game will be a continuously moving platform game, where every few milliseconds the frame
of the game moves automatically to the left, with all objects (rocks and fish), apart from baby
shark which will be constantly placed approximately 10% from the left of the frame, but can
move up and down.

The objects can either be obstacles to be avoided (rocks) or objects to be taken (fish). The user
can click anywhere on the space to place rocks or fish. The system also generates rocks or fish
randomly every second, appearing at the farthest right end of the screen. Rocks will be of
random size (small, medium, large), and fish will be of random size (small, medium, large), with
small carrying 10 points, medium carrying 50 points and large carrying 100 points.
Baby shark has 3 possible actions at each timestep of the game. Move up, move down, or stay
on course. Baby shark must plan ahead to ensure it does not hit a rock, and maximise the points
from the fish it can capture in its trajectory. As more fish and rocks appear, it will need to adjust
and re-plan to take into consideration the new information.

Baby Shark was solved using Deep Reinforcement Learning via the Proximal Policy Optimisation Algorithm and Behavioral Cloning.

-- Root Folder --

--Gamefiles

-Contains Scripts, Audio Files, models.. etc (A README can be found within this folder for further guidance).

--GameExecutables

-Contains two build versions of the final game, (IM -> Imitation Learning, PPO -> Proximal Policy Optimization).
	  (Simply click the .exe file to launch the game!)
