# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Austin Lake**

Time spent: **4** hours spent in total

Link to project: https://glitch.com/~austinlake04-memory-game

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
src='http://i.imgur.com/link/to/your/gif/file.gif'


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
When trying implement a random pattern at the start of that game, my program experienced some issues trying to find the id's of my buttons in the lightButton function.
In the Developer Tools, it would says "Uncaught Type Error: Cannot read property 'classList' of null".
Additionally, when trying to speed up the clue playback each turn, my game would not play any sound when displaying a clue.
ue to time constraints and limited knowledge with web development,
I was unable to resolve the issue and had to scrap the implementation of these optional features for the time being.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
How do the various programming languages (HTML, Javascript, and CSS) communicate with each other and utilize the information store on each file?
Is there some sort of code conversion happening on the back end to make these different programming languages compatible?
Could other programming languages be substituted out for the ones we use in this project (i.e. use Python instead of CSS, or C++ instead of Javascript)?
What are some advantages and disadvantages to using HTML, Javascript, and CSS in a web development setting over other programming languages?
How can you integrated API's int web development projects like this to make use of large datasets already available to programmers.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If given a few more hours to work on this project, I would spend more time adding opitional features to make the game more complex.
I did not have time to implement some optional features such as the random pattern, 3 mistakes, guess time limitations, or improving on the audio and appearance of game buttons.
Additionally, I would take some time to polish up the UI of the game to make it more appealing and enjoyable for users to play.


## License

    Copyright Austin Lake

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.