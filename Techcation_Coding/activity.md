### @hideIteration true 

<!-- Minimal starter: only a teleport helper -->
```template
player.onChat("tele", function () {
    agent.teleportToPlayer()
})
```

<!-- Blocks: curated palette -->
```blocks
// --- Chat & basic structure ---
player.onChat("run", function () {})
player.say("Ready!")

// --- Agent core controls ---
agent.teleportToPlayer()
agent.move(FORWARD, 1)
agent.move(BACK, 1)
agent.turn(LEFT_TURN)
agent.turn(RIGHT_TURN)
agent.destroy(FORWARD)
agent.place(FORWARD)
agent.collectAll()
agent.setItem(PLANKS_OAK, 64, 1)   // item, count, slot
agent.setActiveSlot(1)

// --- Sensing / decisions ---
agent.detect(AgentDetection.Block, FORWARD)
agent.inspect(AgentInspection.Block, FORWARD)
if (true) {} else {}
if (agent.detect(AgentDetection.Block, FORWARD)) {}
if (agent.inspect(AgentInspection.Block, FORWARD) == GRASS) {}

// --- Loops (bounded & conditional) ---
for (let i = 0; i < 4; i++) {}
while (!(agent.detect(AgentDetection.Block, FORWARD))) {}

// --- Variables & math helpers ---
let steps = 5
steps = steps + 1
0 < 1
true && false
```

# Tinker Coder
## Hackathon
### Welcome!

Welcome to the Hackathon! In this event, you will compete to complete a series of challenges as quickly as you can!

Before you start, please listen to the briefing given by your instructors. Your goal will be to finish the event with as many points as you can, as quickly as you can.

<sub>*You must only use the blocks given here. If you are found to be using other blocks, trying to get around the controls of the map, or building yourself, the map will be reset and you will have to start over. No extra time will be given in these cases.*</sub>
