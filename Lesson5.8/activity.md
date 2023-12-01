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
