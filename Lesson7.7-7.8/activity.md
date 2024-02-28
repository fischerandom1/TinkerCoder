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
agent.till()
agent.setItem(GRASS, 1, 1)
agent.setSlot(1)
agent.detect()

if (true) {}
if (agent.inspect(AgentInspection.Block, FORWARD) == GRASS && false) {} else {}

for (let index = 0; index < 4; index++) {}

while (!(agent.detect(AgentDetection.Block, FORWARD))) {}

let test = 0

player.onTravelled(WALK, function () {
    if () {
        test = 0 + 0
        agent.setItem(randint(0, 10), 1, 1)
    }
})

player.onItemInteracted(IRON_SHOVEL, function () {
})

function doSomething () {
    agent.setAssist(PLACE_ON_MOVE, true)
}

```

# Tinker Coder
## Lesson 7.7-7.8
### Welcome!

In this lesson, you will apply what you have learned to design and build a city.

For more instructions, go to Lesson 7 & Lesson 8 in your book. Be sure to read all the instructions. There are also some sample ideas you may choose to build. 

As you code, make sure you DO NOT delete any of the code that you have successfully used. At the end of the lesson, you can show off what you have built, and your code to your parent/guardian.

<sub>*You must only use the blocks given here. If you are found to be using other blocks, trying to get around the controls of the map, or building yourself, the map will be reset and you will have to start over. No extra time will be given in these cases.*</sub>
