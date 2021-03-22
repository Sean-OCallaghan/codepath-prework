# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Sean O'Callaghan**

Time spent: **3** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [*] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [*] "Start" button toggles between "Start" and "Stop" when clicked. 
* [*] Game buttons each light up and play a sound when clicked. 
* [*] Computer plays back sequence of clues including sound and visual cue for each button
* [*] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [*] User wins the game after guessing a complete pattern
* [*] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [*] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [*] Buttons use a pitch (frequency) other than the ones in the tutorial
* [*] More than 4 functional game buttons
* [*] Playback speeds up on each turn
* [*] Computer picks a different pattern each time the game is played
* [*] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

![](https://i.imgur.com/EuaYshX.gif)



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used no outside resources. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The hardest challenge was creating the array of random variables. I have never used the function described in the tutorial so I had done experimenting. I started with using numbers and console logging the to see what the array would look like. I then proceeed to have an issue of my array including 0 when I only wanted 1-6. I overcame this issue by simply testing the function more and trying to solutions. I added one to my function which made it work perfectly.
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
The only question I have about web development is about the differences in technology. Instead of JS and HTML many developers use React and Angular or View, im curious as to why JS is such a prominent framework and im excited to learn its breath of usefullness throghout this course. Although i have created projects of my own using html and javascript I have never recievied insight as to why JavaScript is such a powerful language. I want to explore all the technologies web developing has to offer. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would create a user interface with increasing difficulty, the user can select a difficulty and the amounf of buttons, guesses and hold time will change. I would also like to add an endless mode where the game will appear to be endless and track the users highest score. I wouldnt think this would be too difficult since you would just need to create a resizable array and keep track of how many correct quesses when he loses. 



## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.