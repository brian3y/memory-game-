# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Brian Y**

Time spent: **#5** hours spent in total

Link to project: https://glitch.com/edit/#!/showy-flash-conifer?path=style.css%3A10%3A18

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] added a gif background 

## Video Walkthrough (GIF)

![](https://user-images.githubusercontent.com/90811892/161194977-a9d3448c-67cf-4ec2-8032-471779cecfd4.gif)
![](https://user-images.githubusercontent.com/90811892/161194999-14873b8c-bd4c-44a1-9f1d-0936f6c60015.gif)
![](https://user-images.githubusercontent.com/90811892/161195008-d305cd4f-1118-4fdd-8379-63e29521cb25.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[ttps://developer.mozilla.org/en-US/docs/Web/API/setTimeout

https://www.w3schools.com/jsref/prop_element_classlist.asp

https://www.youtube.com

https://www.google.com/]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[Before this web development project, I don’t have any experience in HTML/JavaScript/CSS. Figuring out how each line of code affects the website really interests me during the creation of the memory game. I found that understanding the different relationships between HTML/JavaScript/CSS and implementation on the website was really challenging for me. I overcome the challenge of understanding specific methods by doing my own research and reading references from the instruction. For example, the phrase“document.getElementByID” looked really strange to me at first. But as I started to read about the document object model(DOM), I realized the fund isn’t of the document.getElementByID is to find the object and its name. Then I could implement a specific property like classList and use their method like “add” or “remove”. As I did further research on it, I find classList has many useful methods like a toggle or replace. It is read-only but I can use the method to add or remove CSS classes from the actual list. Another method I had a hard time understanding is setTimeout method. I used some other websites like developer.Mozilla.org to figure out how to actually use this method. It first enters the parameter of the method to use in the future, then it asks for the duration of the time to put it in. Finally, it optimally asks for an argument to put it in the methods. The function setTimeout(clear button,clueHoldTime,btn) basically means to call clearButton(btn) in clueHoldTime milliseconds. 
]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[After completing my submission, I had many questions about how to make the website game more user-friendly and interactive.  During the creation of the game, I have noticed many ways to break the game, and I was really curious about ways to optimize it. And can I write codes that will fix the error after reloading or refreshing the page instead of reopening the program? I also think the ways to optimize the program loading time and program response time.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[If I had a few more hours, I would choose to work on finishing up all of the optional tasks and implements some of my ideas on the memory game. One of the features I would like to spend time doing is the counting timer. I had worked on the counting timer feature for a few hours. It was confusing for me to implement a display of 60 seconds counting the clock on the screen. I have figured out the logistics using JavaScript, but I haven’t been able to connect it to HTML and CSS. And other features like making a random pattern and speeding up the game would be really helpful to make my game more playful and competitive. One of the ideas I had is to change the shape of each square to make it more unique. And when you click on it not only the color is gonna change, but the shape can also alter a little bit to make it more realistic. Another thing I want to add is adding a starting page that makes all of the squares disappear unless the user clicks on the start page. This would generate a clearer user interface. ]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/fD2iXCrsWM0)


## License

    Copyright [Brian Yuan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
