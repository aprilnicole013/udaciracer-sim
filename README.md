# Welcome to the UdaciRacer Simulation Game

## INTRODUCTION

This is a partially built-out game that races cars. The game mechanics are this: you select a player and track, the game begins and you accelerate your racer by clicking an acceleration button. As you accelerate so do the other players and the leaderboard live-updates as players change position on the track. The final view is a results page displaying the players' rankings.

The game has three main views:

1. The form to create a race

2. The race progress view (this includes the live-updating leaderboard and acceleration button)

3. The race results view

## HOW IT WORKS
This racing game uses asynchronous methods to achieve tasks. API calls will fetch the cars, tracks, and race ID information. The data recived by the API will create the race selected by the players and return a stream of information lasting the duration of the race, resulting in a final ranking of racers. 


## HOW TO INSTALL

1. Download the code from this repository.
2. Run your preference of `npm install && npm start` or `yarn && yarn start` at the root of this project. Then you should be able to access http://localhost:3000. Open this link in your browser.
3. To run the server, run the associated command in your terminal at the root of the project:

| Your OS               | Command to start the API                                  |
| --------------------- | --------------------------------------------------------- |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-osx`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux` |

Note that this process will use your terminal tab, so you will have to open a new tab and navigate back to the project root to start the front end.

** If you are using a windows machine: **
1. `cd` into the root of the project containing data.json 
2. Run the following command to add the environment variable:
```set DATA_FILE=./data.json```



