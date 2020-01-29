<img src="https://miro.medium.com/max/300/1*h9G7gjWQeQVwqkbhHVvOQg.png" alt="p5"
	title="Let's get started with p5 :-)"
	align="left" width="230" height="230"
	style="margin: 50px" />

# p5workshop
For Processing Community Day Copenhagen 2020

## Useful links
- The p5 online editor: [editor.p5js.org](https://editor.p5js.org/)
- p5 reference: [p5js.org/reference](https://p5js.org/reference/)

### Youtube channels
- [The Coding Train](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
- [Kreativ Kodning](https://www.youtube.com/channel/UCRSqTiVe7Rho95hNtd3hJBQ/playlists) (in Danish)

# 1. Create your own masterpiece
<img src="https://ctl.s6img.com/society6/img/_iGYmenyD9ZbVzWAyJgD4yoDm2o/w_700/prints/~artwork/s6-original-art-uploads/society6/uploads/misc/ae0e77aad5074016ac4a2f01fe59c47d" alt="Kandinsky"
	title="Wassily Kandinsky: 'Blue Painting'" align="right" width="250" height="250" />

## Exercises

### 1.1 Setting up and choosing background color
- Log in to the p5 editor using a Google or Github account. Or create an account if you have neither of those.
- Choose a canvas size fitting your tastes and screen size.
- Make the background a shade of gray.
- Make the background yellow.
- Make the background your favorite color.

This [Color picker](https://www.google.com/search?q=color+picker) might be helpful.

### 1.2 Dots, stroke, and stroke weight
- Put a large, green dot at the upper right part of the canvas.
- Create a small group of dots of different sizes and colors at a region of the canvas of your choice. They should have coordinate sets close to each other, but not identical.

### 1.3 Rectangles
- Make a rectangle with stroke and fill colors of your choice so that it does no overlap the group of dot from last exercise.
- Make a rectangle that frames the group of dots. Make sure it has no fill.


## Finally, create your own piece of abstract art
Use what you've learned to compose a work of your own. Use the examples below, either as inspiration, or choose one to recreate:

[A collection of inspiring works of art](https://docs.google.com/presentation/d/e/2PACX-1vTOWjpHnjLNllezpdzjXKan4EI-zMAwuV4N_PcARcsQja_aY5P1p5fRPr2v82uxmYgFGSlULZ5jtFWd/embed?start=false&loop=false&delayms=3000&slide=id.g3f70b3232d_0_27) - *Compiled by Esther Hersh*

**When you're done, send the link to your sketch to p5workshop2020@gmail.com - I will make a gallery of the contributions**

# 2. Interaction using built-in variables

## Exercises

### 2.1 Width and height of canvas
- Use the built-in width and height variables to draw a circle centered at the middle of the canvas.
- Changes the size of the canvas in the createCanvas command, and check that the circle is now drawn at the new center.

### 2.2 Clicking the mouse
- Move the background command from draw to setup, so that the draw function is empty (If in doubt, consult picture to the right) Consider what differences this will make.
- Add a mousePressed function to the sketch.
- In the mousePressed function, draw a dot at a random position on the screen. See the cheat sheet for how to generate random numbers for the coordinates.
- Try clicking the mouse :D

### 2.3 Using the mouse to draw
- This might work better in a fresh sketch, so feel free to save your work and start a new one.
- Draw a dot at the current mouse position.
- What happens if, instead of calling the background command in draw, you call it setup (i.e. only once)? 
- What happens if you give the stroke color some alpha? (If in doubt, see cheat sheet)
- Remove the alpha from the stroke color. Put the background command back into draw. Give the background color some alpha instead. What happens?
- Change the sketch, so that instead of a dot, a line from the previous mouse position to the current one is drawn.

# 3. Animation using variables

# 4. Images
[Start with this sketch](https://editor.p5js.org/kwichmann/sketches/q_v3Mu06)

## Exercises

### 4.1 Displaying images
- Open the file tab (arrow next to sketch), and inspect the names of the picture files.
- Choose one of the files names, and write it in the quotes of the loadImage command.
- Display the image on the canvas - you choose where.
- Change the size of the picture.
- Change the color of the picture by tinting it.
- Search the p5 reference for the filter command, and try applying a filter to the image.

### 4.2 Make your own
- Find an image online and upload it to your sketch. Transparent png files works best.
- Display the image on the canvas.
- Make the way the image display mode interactive, whether trough mouse or keyboard input.

# 5. Sound
[Start with this sketch](https://editor.p5js.org/kwichmann/sketches/0fBDR4iE)

The song "Circle" by the band [Fail to Die](https://www.facebook.com/fail2die/) (whom, I may add, have a particularly charming guitar player) is already added to the sketch and loaded into a variable.

## Exercises

### 5.1 Playing sounds
- Start playing the song by adding a command to the setup function.
- Set a playback rate for the song. What happens if it's greater than one? Smaller than one? Negative?
- Make the playback volume and/or the sound panning depend on the position of the mouse.

### 5.2 Add your own
- Find a sound file and upload it to one of your sketches.
- Add sound to the sketch.
- Add an interactive element to the playback.

**Once again, links to your cool sketches are welcome at p5workshop2020@gmail.com**
