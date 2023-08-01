In this project,an **Emoji Game** is developed.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/emoji-game-output-v2.gif" alt="emoji-game-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

The app has the following functionalities

- Initially, the _Score_ and _Total Score_ for the current game is **0**
- When an **Emoji** is clicked,

  - If it is not the same as any of the previously clicked emojis, then the _Score_ is incremented by one
  - If all the emojis are clicked exactly once

    - [Won Game](https://assets.ccbp.in/frontend/content/react-js/emoji-game-won-game-lg-output.png) view is displayed

  - If it is the same as any of the previously clicked emojis
    - [Lose Game](https://assets.ccbp.in/frontend/content/react-js/emoji-game-lose-game-lg-output.png) view is displayed
  - If the score achieved in the current game is higher than the previous scores then the _Top Score_ is updated accordingly

- When the _Play Again_ button is clicked, then can to play the game again
  - The _Score_ value will be reset but not the _Top Score_ value
