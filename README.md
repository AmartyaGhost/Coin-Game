# Coin-Game using Quantum Computation

A quantum coin game to illustrate the power of quantum superposition and interference

The Coin Game
Two players, A(lice) and B(ob), play a coin game.

The game starts with the coin showing Heads.
Player A starts and may either turn the coin or leave it as is.
The moves are hidden, i.e. not revealed to the other player.
B may now also turn the coin or leave it as is.
A then has the third and final move.
Now the coin gets revealed.
If it shows Heads, A wins; if it shows Tails, B wins.
This notebook implements the coin game using Qiskit, an SDK by IBM to program quantum computers.

On three separate slides, the players can make their choice to either turn the coin (apply an "X-Gate") or leave it as is (apply an "id-Gate" / identity-Gate).
Heads is encoded by "0", Tails encoded by "1".
At the end, the quantum program evaluates the moves and declares the winner.

In a second phase, one player will be allowed to use an additional gate ("coin move"), which is only available in the Quantum world: the "Hadamard Gate".
Will this change the game?


Some Quantum Theory related to this Coin Game:

![image](https://github.com/AmartyaGhost/Coin-Game/assets/103167689/d9b89c14-0189-4b9f-9491-bada540d32b6)
