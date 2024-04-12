
### @hideIteration true 

<!-- block combinations that will show up by default in their workspace -->
```template
player.onChat("c1start", function () {
    agent.teleport(world(18, 67, 30), SOUTH)
})

player.onChat("c1run", function () {
})

player.onChat("c2start", function () {
    agent.teleport(world(3, 67, 30), SOUTH)
})

player.onChat("c2run", function () {
})

player.onChat("c3start", function () {
    agent.teleport(world(26, 67, 21), NORTH)
})

player.onChat("c3run", function () {
})

player.onChat("c4start", function () {
    agent.teleport(world(3, 67, 21), NORTH)
})

player.onChat("c4run", function () {
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

if (true) {}
if (agent.inspect(AgentInspection.Block, FORWARD) == GRASS && false) {} else {}

while (!(agent.detect(AgentDetection.Block, FORWARD))) {}

```

# Tinker Coder
## Hackathon
### Welcome!

Welcome to the Hackathon! In this event, you will compete to complete a series of challenges as quickly as you can!

Before you start, please listen to the briefing given by your instructors. Your goal will be to finish the event with as many points as you can, as quickly as you can.

<sub>*You must only use the blocks given here. If you are found to be using other blocks, trying to get around the controls of the map, or building yourself, the map will be reset and you will have to start over. No extra time will be given in these cases.*</sub>
