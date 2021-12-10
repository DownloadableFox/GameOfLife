# GameOfLife
Simple Conway's Game of Life implementation made in HTML5 and JavaScript! 

> I made this because I was bored... Feel free to fork and create push requests with features and fixes! -DownloadableFox (Author)

The idea behind this repository is to keep it simple **(just one html file)**, and frameworks! Just plain JavaScript and CSS. It's made specifically as a safe repository to new people at GitHub and programming in general. Feel free to contribute.

#
### How it works

You have serveral ways to move arround including using the mouse and keyboard:

**Space** Pause & Resume the game

**Left Button** Move in space (Alternatively you can use the **arrows keys**)

**Right Click** Toggle cell (Only works when the game is paused)

**Mouse Wheel** Zoom in and out (Alternatively you can use the **,** and **.** keys respectively)

> The current game is infinite, or at least number max in JavaScript. It works by using projection matrix instead of a fixed grid/matrix

#
### Running
As it's just an html file, you can open it with your browser or host it with any static web server. I normally use *serve* (npm package).

**To use/install serve you'll need to have npm and node**


1) To install serve you can open the serminal and run:
```bash
npm install -g serve
```
2) Afterwards, you can start up a server in the local directory with serve:
```bash
serve -l 3000
```
Your server should be running and you can access it by clicking [here](http://localhost:3000)*
#
### Images
![Game Of Life](https://user-images.githubusercontent.com/58178791/145637104-96bfd81d-82ae-44e1-9542-7da10976c805.png)

#
Made with love by: @DownloadableFox <3
