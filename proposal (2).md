# Proposal

## What will (likely) be the title of your project?

Pong

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

A cool and fun pong game that I make from scratch. I will be using LOVE framework to run my code.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

The project is based on a typical version of Pong, but with single-player mode added by programming an AI agent for one or both of the paddles. Instead of the relying on keyboard to control the tracking and hitting, the single-player mode uses an autopilot to follow the ball and automatically go up or down as needed to knock it back across the screen. It will include Pong physics, collision detection, score keeping, and an autopiloted single-player paddle.

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

I would say it relates to data analytics since we're writing a script to collect data.

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

Curtis R Ellis-Johnson, curtis.ellis-johnson@temple.edu, Section 04
Calvin Wills, calvin.wills@temple.edu, Section 04
## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

a GOOD outcome for our final project would be that the program works perfectly, we followed the plan accordingly but nothing special.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

a BETTER outcome would be making the Pong unique, like adding a cool mode or making the visuals better.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

the BEST outcome would be for us to create a masterpiece that ends up a 100.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

My next steps is to download LOVE framework and accessing the code repository. I will need to learn the syntax of Lua, especially object-oriented scripts, table structures, and how event-driven update loops work in LÖVE's love.update(dt) function. Research will be necessary into the coordinate space in 2D space (specifically offsets in $Y$-coordinate between the height center of the paddle and the ball) and the design of a game-loop that informs the puck how fast it needs to be moving in order to make the AI undefeatable (if working alone). I am working alone on this project, so I will be responsible for all code reading, implementation, testing, and documentation. I will be working with Curtis and Calvin but I will focus on implementing the AI tracking logic within Paddle.lua and main.lua, while one of them handle refactoring the game states, testing edge-case collisions, and adding optional difficulty modifiers.
