This is a breakdown of the most important contents of the game files:

--Gamefiles--

--Assets
	--Animation
		All custom backgrounds, custom animations (made with sprite sheets) and other handdrawn images.
	--AudioFiles
		Audio clips used for the game
	--AudioScripts 
		The c# code used for audio, aswell as UI button logic.
	--Brains
		The final two models trained and used for the game (PPTraining -> PPO algorithm && ImTraining -> Imitation Learning) 
	--EnviromentScripts
		All the C# code used to create the main enviroment of the game
	--Scenes
		All the four different scenes used for the main game (Main Meu, Settings Menu, Game itself etc..)	
--config
	The two configurations files used that allowed tweaking of different configurations for the different algorithms (such as max steps, LR, epsilon etc)
--Demo
	The three recorded demos played by a human player used to feed to the GAIL and Behavioural Cloning algorithms 
--results
	This folder contains all the different training attempts that occurred throughout the course of the assignment for PPO and Imitation Learning



	