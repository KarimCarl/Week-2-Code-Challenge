# Bot Battlr.
This is the Bot Battlr the one and only spot in the known universe where you
can custom build your own Bot Army!

## Instructions

You’ll be building out a React application that displays a list of available bots, among other features. This challenge is testing is your ability to follow given instructions. While you will definitely have a significant amount of freedom in how you implement the features, be sure to carefully read the directions for setting up the application.

## Setting Up

1. In project directory, create a db.json file and use provided for the server DB.
2. Run this command to get the backend started: json-server --watch db.json
3. In a new terminal, run npm start. This will run your React app in a new port.

Note that this app uses 'Semantic UI' for styling which you can install by running 'npm i semantic-ui-react'

## Endpoints
The base URL for the backend is: http://localhost:3000

## Deliverables

A user should be able to:
    - See profiles of all bots rendered in BotCollection.
    - Add an individual bot to my army by clicking on it. The selected bot should render in   'YourBotArmy' component. The bot can be enlisted only once. The bot does not disappear from the BotCollection.
    - Release a bot from my army by clicking on it. The bot disappears from the YourBotArmy component.
    - Discharge a bot from their service forever, by clicking the red button marked "x", which would delete the bot both from the backend and from the YourBotArmy on the frontend.



### Other Deliverables
Bonus deliverables 

A user should be able to:
    - Choose if I want to enlist a bot into my army or just see their data. Clicking on the card  should instead display a show view (BotSpecs) for that bot, which should replace BotsCollection. BotSpecs should have two buttons: one to go back to the list view and another to enlist that bot.
    - Sort bots by their health, damage or armor. For this, create a new component, SortBar.
    - When I enlist a bot it will be removed from the BotCollection and added to YourBotArmy.
    - Filter bots by their class. We can select a few filters at the same time.
    - Sort bots by their health, damage or armor. For this, create a new component, SortBar.
    - Only enlist one bot from each bot_class. The classes are ["Support", "Medic", "Assault", "Defender", "Captain", "Witch"].

## Conclusion
This app allows a user to build your own Bot Army!
A user can be able to add or delete a bot.
Building this project with beginner skills in React was obviously very challenging. I needed a lot of help from friends and online tutors to complete this project. Hopefully in the future, with more experience, I can build this without the use of tutors and tutorials seamlessly.


## Author: 
* **Charles Ndung'u** - *Initial work*-[KarimCarl] (https://github.com/KarimCarl)


Status:  Maintained, and is currently in development

Version:
    v0.1.0


## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
Copyright (c) 2022 **Charles Ndung'u**