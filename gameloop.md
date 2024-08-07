# The Game Loop

I believe that to understand how to mod, we have to start by understanding the game loop. This means understanding, roughly, what the game is doing every tick. 

First, what is a 'tick'? Well a 'tick' is a unit of time where the game runs code. In Victoria 3, we have a few ticks, mainly the daily tick, the weekly tick and the monthly tick. Most code is ran on one of those ticks with the notable exception of [GUI], which is run when players click somewhere. For now, though, we can say that all code is ran on those ticks.

Now, what exactly is being run on those ticks? Well, a lot of it is code related to the game's simulation, which we do not have access to. This may interact with our code, particularly [Scripted Types and Content]. There is also another important thing that is being run here, and that is [On Actions].

All throughout this, we will be working on a fun little system that allows us to send our IGs on Diplomatic Missions to foreign countries.

[Onto On Actions](onactions.md)