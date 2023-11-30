### @hideIteration true 

<!-- block combinations that will show up by default in their workspace -->
```template
player.onChat("tele", function () {
    agent.teleportToPlayer()
})
```

<!-- blocks you want available to players, based on js code -->
```blocks
player.onChat("run", function () {})

agent.teleportToPlayer()
agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
agent.place(FORWARD)
agent.destroy(FORWARD)
agent.setItem(GRASS, 1, 1)
agent.setSlot(1)
agent.detect()

for (let index = 0; index < 4; index++) {}

while (!(agent.detect(AgentDetection.Block, FORWARD))) {}

```

# Tinker Coder
## Lesson 5.5
### Welcome!

In this lesson, you will apply what you have learned to decorate the area around the house behind you.

For more instructions, go to Lesson 5 in your book. Be sure to read all the instructions. There are also some sample ideas you may choose to build. 

As you code, make sure you DO NOT delete any of the code that you have successfully used. At the end of the lesson, you can show off what you have built, and your code to your parent/guardian.

*You must only use the blocks given here. If you are found to be using other blocks, or building yourself, the map will be reset and you will have to start over. No extra time will be given in this case.*
