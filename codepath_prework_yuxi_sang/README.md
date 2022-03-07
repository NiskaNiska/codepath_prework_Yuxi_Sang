# codepath_prework

Light and Sound Memory Game

# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Yuxi Sang**

Time spent: **15** hours spent in total

Link to code: https://glitch.com/edit/#!/quickest-delicious-hammer?path=script.js%3A102%3A20

Link to project: https://quickest-delicious-hammer.glitch.me/

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Users are allowed to select from six levels of difficulities: very easy(5), easy(8), medium(10), hard(20), very hard(30), ??????(30)
- [x] The remaining attempts are displayed to the users.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/wjZ4c8z.gif)
![](https://i.imgur.com/emHU8hH.gif)
![](https://i.imgur.com/SOoroaf.gif)
![](https://i.imgur.com/q48pata.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   I refer to Codepen when searching how to display images onclick. Also, I got resources from W3schools, stack Overflow, and Web Dev Simplified. And my friend Greg gave me advice on setting levels of difficulties.
   
2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   I spent some time inserting images into the game button. I found images online, imported them into Assets, and got their links to the HTML file without problem. But I was confused what is the next file to edit. The instruction suggests editing style.css to add CSS rules. But that's not enough. I would still need to modify script.js by        adding two functions showImage() and removeImage(), calling them separately in startTone() and stopTone(). In this way, the images work just we expected. It shows when I am clicking the game button but hides after click.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   The web I just dedigned is fundamental, but it got me into the track and arises my interest in how to design a real website, for example, with parallax scrolling feature. I would continue to learn front-end developement framework and libraries like React and Angular to upgrade my website.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   I would give the users more flexibility by encouraging them to add more buttons and move the buttons around to fit their own styles.

## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)

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
