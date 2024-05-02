### @hideIteration true 

<!-- block combinations that will show up by default in their workspace -->
```template
player.onChat("l", function () {
    agent.turn(LEFT_TURN)
})
player.onChat("r", function () {
    agent.turn(RIGHT_TURN)
})
player.onChat("a", function () {
    agent.turn(LEFT_TURN)
    agent.turn(LEFT_TURN)
})
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

for (let index = 0; index < 4; index++) {}

```

# Tinker Coder
## Module D Lesson 2
### Welcome!

In this lesson, you will learn how to make the Minecraft Agent repeat its actions with loops
