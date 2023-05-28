# Endless Runner

Developed with Unreal Engine 5

POSTER:
![CyberRunner_Poster](https://user-images.githubusercontent.com/72225859/223472878-c43633f4-3838-4727-8e6b-fdd2420bd73b.jpg)


Video DEMO for mobile version of the game: https://youtube.com/shorts/mWcLPC1slTo

Video DEMO for PC version of the game: https://youtu.be/eRsTGW3zypk



Design Document for:


Cyber Runner

The Ultimate High-Speed Futuristic Game




All work Copyright ©2023 by OOP Team

Written by Andrei Tofan and Fuad Godzhaev

Version # 1.00 
 
Design History

Version 1.10

1.	I rewrote the section about what systems the game runs on.
2.	I incorporated feedback from the team into all parts of the design however no major changes were made.
3.	Just keep listing your changes like this.

Version 2.00

1.	Pairing down of the design scope. (Scope, not design)
2.	More detailed descriptions in many areas, specifically A, B and C.
3.	Story details.
4.	World layout and design.

Version 2.10

1.	Minor revisions throughout entire document.
2.	Added “User Interface Appendix”.
3.	Added “Game Object Properties Appendix”.
4.	Added concept sketch for world.
Game Overview

Philosophy

Cyber Runner is a fast-paced, action-packed PC game made with Unreal Engine. We are working on developing a must-play game for fans of action and adventure games. We are aiming to design a cyberpunk world where players can take on the role of a runner, tasked with navigation through a futuristic cityscape filled with obstacles, power-ups and points to collect. The game will include stunning, high-quality graphics and immersive sound effects, which enhance the player’s experience.

Common Questions

What is the game?

Cyber Runner is an exhilarating PC game that takes players on a high-speed journey through a futuristic, cyberpunk world. As a runner, players must navigate through a futuristic cityscape filled with obstacles, while collecting points and power-ups. The game's stunning graphics and immersive sound effects create an intense and captivating experience. With speed increasing, Cyber Runner offers a challenging and engaging gameplay experience. Overall, Cyber Runner is an action-packed adventure that is sure to satisfy fans of the genre.

Why create this game?

	We believe that Cyber Runner’s futuristic setting and high-speed gameplay will offer the opportunity for unique and immersive gameplay experience that can attract players seeking a thrilling adventure. We also believe that there is a demand in the market for a game like Cyber Runner, and we see an opportunity to capture new audience and compete in a less crowded market.

Where does the game take place?

The Cyber Runner environment is a futuristic, cyberpunk world that features a bustling, neon-lit cityscape filled with skyscrapers and technological marvels. The cityscape is located in space where planets can be observed. The environment is immersive and engaging, with high-quality graphics that create a sense of depth and dimensionality. Overall, the Cyber Runner environment is an exciting and thrilling world that draws players further into the game's story and gameplay.

What do I control?

The task of the player in Cyber Runner is to navigate through a futuristic, cyberpunk cityscape as a "runner" while collecting points and power-ups. The runner must dodge obstacles while moving through the environment at high speeds. The player's goal in Cyber Runner is to achieve the highest score possible and emerge as the ultimate runner.

How many characters do I control?

Cyber Runner allows you to control a single character during gameplay.

What’s different?

Cyber Runner offers several unique features and gameplay elements that set it apart from other games in the market. Firstly, the game's cyberpunk setting and high-speed gameplay create an immersive and thrilling experience that is unmatched by other games in the genre. 

The game's stunning graphics and immersive sound effects create a sense of depth and dimensionality that is unparalleled in the market. The game's futuristic cityscape, neon-lit environments, and stunning visual effects create a unique and captivating experience that draws players further into the world of Cyber Runner.

Overall, Cyber Runner's unique features, gameplay elements, and immersive experience set it apart from other games in the market and make it a compelling choice for players seeking a high-speed, cyberpunk adventure.


Feature Set

General Features

Endless world
Sci- fi Character
3D graphics
32-bit color

Multiplayer Features

N/A

Gameplay

Futuristic environment
Bustling, neon-lit cityscape
Skyscrapers
Technological marvels. 
Space scene
Planets
Immersive and engaging
High-quality 




Key Locations

In Cyber Runner, the game takes place in a futuristic sci-fi setting with a variety of key locations. One of the most significant locations in the game is space, which serves as the primary setting for the game's action-packed gameplay. Players will have the opportunity to explore a range of different environments throughout the game, including planets and asteroids. The game's space setting also provides a visually stunning backdrop for the game's action, with breathtaking views of stars, nebulas, and distant planets.

Overview

	In Cyber Runner, the game is rendered using the Unreal Engine, a powerful and highly customizable game engine. The engine uses a variety of advanced rendering techniques to create realistic and immersive visuals, including dynamic lighting, shadows, and particle effects.

One of the key rendering techniques used in Cyber Runner is deferred rendering, which allows for a high level of visual fidelity and realism. This technique uses multiple passes to render the scene, allowing for a wide range of lighting and shadow effects. This means that light sources can cast realistic shadows, and the game's environments can have a more natural and organic feel.


Game Engine

Overview

Unreal Engine is a game development engine and suite of tools created by Epic Games. It is a powerful and versatile game development tool used by developers worldwide to create video games, virtual reality experiences, and other interactive content.

Unreal Engine is known for its advanced graphics rendering capabilities, allowing developers to create stunning visuals and realistic environments. It also provides developers with a suite of tools for creating game logic, scripting, and physics simulations, making it an all-in-one solution for game development.

Unreal Engine is widely used by developers of all levels, from indie developers to major game studios, and has been used to create popular games such as Fortnite, Gears of War, and Batman: Arkham Asylum. Additionally, Unreal Engine has a robust community of developers who share their knowledge and resources, making it a supportive and collaborative environment for game development.

Game Engine Detail #1

Unreal Engine keeps track of several aspects of Cyber Runner gameplay, including player movement, interaction with the environment, collision detection, physics simulation, and enemy behavior. It also keeps track of the game's scoring and point system, as well as any power-ups or bonuses collected by the player.

Additionally, Unreal Engine tracks the game's audio and visual effects, including sound effects, background music, and visual effects such as particle effects, lighting, and animation. It also tracks the game's user interface, including menus, options, and settings.
Collision Detection

Unreal Engine uses a physics engine to handle collisions between game objects in Cyber Runner. The physics engine is responsible for calculating the physical interactions between objects, including collisions, gravity, and momentum.

When a collision occurs in Cyber Runner, Unreal Engine detects the collision and calculates the forces involved. The physics engine uses these forces to simulate the resulting motion of the objects involved in the collision.


Lighting Models

Overview

In Cyber Runner, the Sky Light is an important component of the game's lighting system. It is responsible for providing ambient lighting and helps to create the game's overall lighting atmosphere and mood.

The Sky Light in Unreal Engine captures the color and lighting information from the sky and applies it to the entire scene, creating a realistic and natural lighting effect. The Sky Light also casts dynamic shadows, allowing for more realistic and engaging gameplay.

Game Characters

Overview

	Cyberpunk Street Boy Character
Fully compatible with Epic skeleton and Epic's starter animation pack.
Live Link Face support with fully working Morph Targets / Blendshapes.
Separated modular character parts (body, hair, head, jacket, leg, mask A, mask B, mask C, shoes & vest).
Merged character's parts option.
Includes sword and its sheath.

Creating a Character

The game is set to a one character which it is not necessary to implement a create character function.


Overview

	Describe the single-player game experience in a few sentences.
The player is running at high speed through a futuristic environment.

