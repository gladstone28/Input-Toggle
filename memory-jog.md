link to lesson

https://www.codecademy.com/courses/learn-phaser/lessons/learn-phaser-basics/exercises/input

link to AI

https://chat.openai.com/c/fd2abeb4-094d-4ecf-9f42-a25ba851efe5

link to source folder

/c/Users/glads/Downloads/phaser-game/Input-Toggle


#### LEARN PHASER: BASICS

# Input

It’s time to make a game that we can actually play! Phaser gives us ways to handle mouse and keyboard input, so that we can trigger events to happen in the game. In this exercise we’re going to look at ways to use the mouse, but we’ll be covering keyboard input in our next exercise.

In order to interact with a GameObject, we need to call the setInteractive() method on it. The setInteractive() method tells Phaser to listen in for interactive events on the GameObject.

After calling setInteractive() we can provide the GameObject with an event handler. The event handler is a function that gets called when a specific interaction has happened to the GameObject. We’re going to look at four different possible events in this exercise:

- 'pointerdown': this event gets called when the mouse button has been pressed (but not released) on the GameObject.
- 'pointerup': this event gets called when the mouse button has been released over a GameObject.
- 'pointerover': this event gets called when the mouse pointer hovers over the GameObject.
- 'pointerout': this event gets called when a mouse pointer that was hovering over a GameObject is moved somewhere else.

