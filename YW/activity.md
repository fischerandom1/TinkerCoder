
### @hideIteration true 

<!-- block combinations that will show up by default in their workspace -->
```template

player.onChat("c1run", function () {

})


player.onChat("c2run", function () {
})


player.onChat("c3run", function () {
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
agent.place(FORWARD)
agent.setItem(GRASS, 1, 1)
agent.setSlot(1)

if (true) {}
if (agent.inspect(AgentInspection.Block, FORWARD) == GRASS && false) {} else {}

for (let index = 0; index < 4; index++) {}
while (!(agent.detect(AgentDetection.Block, FORWARD))) {}

```


### Welcome!

Welcome to the Minecraft ! In this you will learn how to program the agent to complete all the task!

