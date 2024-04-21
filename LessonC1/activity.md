player.onChat("tele", function () {
    agent.teleportToPlayer()
})

player.onChat("run", function () {})

agent.teleportToPlayer()
agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
