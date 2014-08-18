BB-OS-10-Turn-Based-RPG
=======================

A turn based RPG for the Blackberry OS 10 device

Name: Brian M
Email: cro_mos@hotmail.com
Language: C#
Dev Tools: Unity 4.5.0f6

Purpose: I'm looking to make an enjoyable turn based RPG in the vain of Final Fantasy. I'm developing the game in Unity so that it can be ported to all the different mobile platforms. I currently have a Blackberry Z10 and the envirment is setup for that.

Experience: This is my first program in C# and Unity so I will be learning along the way. It is also my first real Github project so I'm excited to learn some new skills.

Vision: This game is made for modern mobile devices but I'm looking for a retro theme. I'm looking to utilize the touch screen for character movement and menu selection. I will not be using a virtual job stick because they are enoying. I do not have plans for the story. I want to create the framework around which a story can be easily added. 

What has been done so far: I have created the project and implemented a couple of features so far. 

World Map Movement: I am using the A* Pathfinding Project as the base for my characters path finding. I want the player to click somewhere on the screen and have the character avoid all obstacles while finding the quickest path. I'm working on a way to easily block off obstacles for the pathfinding script. I want to be able to easily add invisible obstacles that go over the map for each area. 

Animation: I have the basic character animation setup. This is currently not working after implementing the touch movement script. 
Graphics: I have using all temporary graphics at this point. I would be willing to use graphics from other people but I want the concentration to be on functionality and gameplay.

Battle screen: I have some of the layout created but I'm not 100% sure about the directly. I have it setup now where the player is on the right side and AI on the left. I've seen a good RPG recently where the player is at the bottom. I might want to take that approach. Right now I will stick to the classic view.

AI: This game doesn't really require AI. Maybe program a bit for the battles to make it a little more challenging.

Saving the game: I'm using Unity Serializer as it looks like a great free utility. I have not tested or implemented the save feature yet.

Main Game Menu: This needs a lot of work. It does have a button for new game that switches scenes. I still need to implement the load game screen so people can continue a previous game. 

In Game Menu: Nothing yet. Need to implement an intuitive way of easily adding and removing equipment and adjusting abilities. 

If you've read this far I will post some branches and fixes/tickets that you can work on if you wish to help.
