
### @hideIteration true 

<!-- block combinations that will show up by default in their workspace -->
```template

player.onChat("c1run", function () {

})

player.onChat("c1tele", function () {
  agent.teleport(world(287, 19, -200), WEST)
})

player.onChat("c2run", function () {
})

player.onChat("c2tele", function () {
  agent.teleport(world(178, 19, -194), SOUTH)
})

player.onChat("c3run", function () {
})

player.onChat("c3tele", function () {
  agent.teleport(world(178, 19, -158), SOUTH)
})

player.onChat("c4run", function () {
})

player.onChat("c4tele", function () {
  agent.teleport(world(178, 19, -110), SOUTH)
})

```

<!-- blocks you want available to players, based on js code -->
```blocks
player.onChat("run", function () {})

agent.teleport(world(3, 67, 21), NORTH)
agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
agent.destroy(FORWARD)
agent.detect()
agent.place(FORWARD)
agent.setItem(GRASS, 1, 1)
agent.setSlot(1)

if (true) {}
if (agent.inspect(AgentInspection.Block, FORWARD) == GRASS && false) {} else {}

for (let index = 0; index < 4; index++) {}
while (!(agent.detect(AgentDetection.Block, FORWARD))) {}

```

# Techcation
## Minecraft Addons
### Welcome!

Welcome to the Minecraft Addons! In this event, you will apply what u have learned to complete the tasks ahead


