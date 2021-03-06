# Rock Paper Scissors

The purpose of this repository is to model a game of rock-paper-scissors.

## The Game

The rules of rock-paper-scissors are simple.

It is a two player game where each player chooses rock, paper or scissors and the two moves are compared to evaluate who wins the round.

- Rock beats scissors
- Scissors beats paper
- Paper beats rock

---

## Your job

The current implementation plays 5 rounds of the game, prints the results out to the screen and then stops.

We would like you to...

- Calculate the game winner by totaling the number of rounds won for each player. A draw (equal number of rounds won) is possible.
- Write the results of each round and the final game result to a file on disk. The format of the file doesn't matter.
- Keep the unit test coverage above 80% method coverage.
  - You can run the coverage report in a terminal by running `dotnet test /p:CollectCoverage=true /p:Threshold=80 /p:ThresholdType=method /p:CoverletOutputFormat=lcov /p:CoverletOutput=./lcov ./RockPaperScissors.Tests`
