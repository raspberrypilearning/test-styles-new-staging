## A Task!

--- task ---

This is an example of a task. You can click the thing to mark it as done, although the app will forget once you've move to another step or navigate to another page.

* a little list
* a list

--- /task ---

--- task ---

### Two tasks adjacent

Who knows what will happen

``` yml
title: The title of the project
hero_image: images/banner.png # The image used on the listing view
subtitle: Project subtitle # Used on the listing view
description: Project description # Used on the listing view
```

--- /task ---

## A Task! With an Ingredient!

--- task ---

This task has an embedded ingredient project. It should display the same in here as it does in isolation:


There's an image in here, too

![screenshot](images/band-ideas.png)

--- /task ---

## A Task! With Hints!

--- task ---

_This_ task has a hints block embedded! Would you just get a load of that! It's like being hit in the face with a hot football boot. Why are they called football boots, because they don't even cover you ankle. Pointless.

--- hints ---
--- hint ---

You'll need to add code to:

* Turn on the Scratch GPIO server
* Set up pin 4 as input

You can then display the input value on the stage, and then move in front of the PIR sensor and see if the value changes.

--- /hint ---
--- hint ---
* Add a broadcast command to set up the Scratch GPIO server, and another broadcast command to set up your input.
  Here's how your code should look (the example uses pin 4 for input):
  ``` ruby
  def hello
    puts 'hello'
  end
  ```

Click the green flag to run the commands above. This will set up Scratch to listen for your input device.

To see your sensor value, click the 'Sensing' blocks section, and click the down-arrow on the slider sensor value block. You can then choose your pin (for example GPIO pin 4), and click the tick box so that the value appears on the stage

--- /hint ---
--- hint ---

* Keep your timer running until input is detected on your GPIO pin. Remember to use the correct sensor value, and the correct number for detecting input, e.g.:
  * Use = 0 for buttons.
  * Use = 1 for PIR and LDR sensors.

* Your timer should repeatedly update your time variable after a short delay. You can choose any number you like, but make sure you have the same number in both wait and change blocks.
--- /hint ---
--- /hints ---

And that's all there is to say about that.

<video width="560" height="315" controls>
<source src="images/gpio-music-box-1.webm" type="video/webm">
Try using FireFox or Chrome for WebM support
</video>

--- /task ---

## Go Away.

Go away!

