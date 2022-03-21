# Pre-work - *Animal Memory*

**Animal Memory** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Mehul Aneja**

Time spent: **10** hours spent in total

Link to project: https://glitch.com/edit/#!/puzzling-deluxe-haddock

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
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [x] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [x] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

* [x] Separate lost game message if you lost because you ran out of time
* [x] Buttons "pop" when clicked
* [x] Button to toggle easy/hard mode
* [x] Easy Mode with consistent playback speed
* [x] Hard Mode with faster playback speed after every round

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Interface and button interactivity
![](https://i.imgur.com/b5xlXK1.gif)

Winning
![](https://i.imgur.com/6rPHgNd.gif) 

Losing because of time run out
![](https://i.imgur.com/s5pYgU1.gif)

Losing because of mistakes
![](https://i.imgur.com/dMCRXEN.gif)



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

For images and reference material:
    
https://www.freeiconspng.com/images/dog-png
https://www.pikpng.com/pngvi/TJTTTb_surprised-cat-480-1058-yawning-cat-transparent-background-clipart/
https://www.seekpng.com/ima/u2q8r5e6q8e6o0q8/
https://www.meme-arsenal.com/en/create/template/474787
https://pngset.com/download-free-png-ycctp
https://stackoverflow.com/questions/20869401/display-an-image-only-when-button-is-clicked
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
https://www.w3schools.com/tags/tag_img.asp
https://www.thesitewizard.com/css/hide-images-on-mobile-website.shtml
https://programminghead.com/how-to-play-audio-in-html-using-javascript/
https://www.w3schools.com/jsref/met_win_setinterval.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

Setting up a countdown timer was proving to be a difficult task for me since I am still in the process of learning JavaScript and was fairly unfamiliar with the setInterval(), clearInterval() and the setTimeout(), clearTimeout() methods. As suggested in the pre-work, I read up on both the methods and tried implementing them in the game. At first, I was very confused about where to place it so it began and stopped at the correct time. Moreover, as per my initial placement, I was running into an issue where the timer would start right as the pattern began playing instead of when the pattern ended. Through a lot of trial and error, I figured out that adding the ‘delay’ variable to the timer ensured that the countdown timer ended after the specified time for each pattern round. 

I also realized that there was a requirement for the clearInterval() method in more than one place, depending on whether the user made a mistake or guessed correctly. I solved this issue majorly through trial and error and it consumed a large chunk of my time. I also ran into some difficulty while adding a hard mode for the game. More specifically, I was running into issues while trying to toggle the hard mode due to a small error. I retraced my steps and reread the code I had most recently added and after a while I discovered that I had forgotten to initialize the hardMode variable while declaring it which led to some runtime errors.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After working on this pre-work project where I haven’t used any frameworks or JS libraries, I am curious to know how much flexibility and versatility standard JavaScript and HTML/CSS offer as compared to a library for JavaScript such as React which makes it much easier to have reusable UI components. I believe I’ll learn more about this as the current spring semester progresses since I’m currently enrolled in a class called Agile Software Development and DevOps which is allowing me to delve deeper into these topics and also allows me to learn through application since I’m required to work with other students on a particular semester-long project. 

I want to know the extent to which I can customize HTML components such as buttons and also if there are other languages which I could use alongside these 3 to further complement my project. I have slight familiarity with PHP and am aware of database languages to store data on servers. I believe these could also be used in similar projects.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more hours to work on this project, I would try to refactor the functions responsible for playing the tunes when buttons are clicked. I would like to try to rewrite them more concisely to make the code more readable and user-friendly, and less wordy. 

As for additional features, I’d like to add a button to control the number of animal buttons, maybe wire it as part of the easy/hard mode button. Make the game more animal themed by changing the background to an animal-themed one. When the user wins the game, all the animal buttons could light up and glow green, or red when the user loses the game.




## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Mehul Aneja]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.




