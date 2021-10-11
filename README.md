## Asteroid Runner

### Open AI Codex

Open AI created an improved there version version of OpenAI Codex, the AI system that translates natural language to code, and released it through their API in private beta. Codex is the model that powers GitHub Copilot, which was built and launched in partnership with GitHub. Proficient in more than a dozen programming languages, Codex can now interpret simple commands in natural language and execute them on the user’s behalf—making it possible to build a natural language interface to existing applications.

The Datacom Foundry have used Open AI codex to create a sample game that can be used to get a better understanding of the playground and it's capability which is in Private Beta.

### Steps

You will need access to the codex private beta to complete these steps:

1. Navigate to the beta console [here](https://beta.openai.com/codex-javascript-sandbox)

2. Copy and Paste the following instructions into the codex playground

```
Make it be smallish.
```

```
Crop it circularly
```

```
Make it be vertically centered; put on the left side of the page
```

```
Animate the rocketship horizontally, bouncing off the left/right walls.
```

```
Go half speed
```

```
Now set background to the colour of space
```

```
When the rocket is clicked, temporarily display some text saying "Firing thrusters!" in white on the current location -- and temporarily speed up by 4x for 0.25 seconds.
```

```
Now add an image of an asteroid: https://d.newsweek.com/en/full/1721338/asteroid.webp?w=790&f=06fbf5f373040ace234e59954c62b58f
```

```
make it to be half the side of the rocketship times 0.75
```

```
Position it absolutely randomly
```

```
Animate the asteroid to move both horizontally and vertically. Use our own speed variables/function name for asteroid movement.
```

```
Set the asteroid speed to be 1.1x the spaceship's speed
```

```
Now track a score. Display the current score in the top right, with label Score.
```

```
Make the score font colour visible
```

```
Make the score 2 times bigger
```

```
Increment the score by 1 point, every 500ms
```

```
Add a variable for recording whether the asteroid is overlapping the ship
```

```
Check for overlap every 10ms
```

```
Add a second variable recording whether, last time we looked, the asteroid was overlapping the ship
```

```
Add another timer checking if the asteroid switched from not overlapping to overlapping. You lose 5 points if so, and a red message is displayed at that location saying "Collision! -5"
```

```
Record start time and whether the player has already won.
```

```
Once the player reaches 250 points, they win! (1) Clear the document, (2) Tell them how long it took in seconds, in green.
```

```
Add a place for the rules at the bottom left side of the page. Make it 30pt and light grey font.
```

```
Change asteroids to "the asteroid" in the rules text
```

```
Create a game name involving running away, placed at the top left of the page in 45pt white.
```
