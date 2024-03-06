# Guess the Mean

In one round, the game allows up to 10 users to play together. The game is as follow: 

1. Each player put up the same stake to the pot. 
2. Once the above commitment phase passed, it get to the running state. In this state, each player takes turn to pick a number between 1 - 100 (secretly), 
and can broadcast an optional msg to all players. 
3. Once all players have picked a number, the mean of these numbers are computed. 
4. The one that picked the number closest to the mean win all the amount in the pot.

The game will be implemented in:

1. Simply on a smart contract and each step is being tracked on-chain.
2. On a smart contract but with state channel. All the steps in #2 will be done in the state channel. The result is broadcast back on-chain and fund dispersed.
3. On a smart contract with zero-knowledge proof, but each steps being tracked on-chain.
4. Combining 2 and 3, the game will run in a state-channel among players, and the final result is uploaded back on-chain with zero-knowledge proof.

Write a tutorial to document your steps in building this project and your learning.
