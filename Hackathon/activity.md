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

if (true) {}
if (agent.inspect(AgentInspection.Block, FORWARD) == GRASS && false) {} else {}

for (let index = 0; index < 4; index++) {}

while (!(agent.detect(AgentDetection.Block, FORWARD))) {}

```

# Tinker Coder
## Hackathon
### Welcome!

Welcome to the Hackathon! In this event, you will compete to complete a series of challenges as quickly as you can!

Before you start, please listen to the briefing given by your instructors. Your goal will be to finish the event with as many points as you can, as quickly as you can.

<sub>*You must only use the blocks given here. If you are found to be using other blocks, trying to get around the controls of the map, or building yourself, the map will be reset and you will have to start over. No extra time will be given in these cases.*</sub>
