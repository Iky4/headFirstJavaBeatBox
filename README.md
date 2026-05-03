# Head First Java BeatBox

This is the final project from the book Head First Java by Kathy Sierra, Bert Bates, and Trisha Gee. It is a BeatBox application where you create music by checking checkboxes. The app connects to a simple, NOT SECURE!!, chat server to receive messages containing other people's BeatBox melodies, which you can then play in your own application.

# HOW-TO

## Start the server

Run 'MusicServer' in your terminal. This opens the server and allows it to receive incoming messages.

## Start BeatBox

Open a separate terminal window while keeping the server running.

Run 'BeatBox' with a required 'String' argument for your name or nickname. This name lets others know who created the beat.

Example:

'''
java BeatBox Iky4
'''

## Create a beat

Use the checkboxes to build your beat pattern.

You can control playback with:

* 'Start' - plays the beat
* 'Stop' - stops the beat
* 'Tempo Up' - increases the tempo
* 'Tempo Down' - decreases the tempo

## Share your beat

When you are happy with your beat, click 'sendIt' to send it to other users. They will be able to play your beat in their own application as long as they are in the same server as you.
