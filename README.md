# Animal Crossing Text Editor!
__Currently in development.__

This Text Editor can edit text from the following games;
* Dobutsu no Mori (Nintendo 64)
* Dobutsu no Mori + (GameCube)
* Animal Crossing (GameCube)
* Dobutsu no Mori e+ (GameCube)

Animal Crossing Wild World, City Folk, and New Leaf may get support at a later date.
___
# Vinny's Tips!
__At least, from the little I've learned.__

I very much only know the bare minimum when it comes to using this thing,
so please bare that in mind when reading this, I'm not a smart coder or
anything. But here's the phrases I've been using when it comes to making
little edits to the dialogue.

___
_If you're going to edit the text, please be sure to replace the message_data.bin AND message_data_table.bin, the game will bug out if you do not do this._
___
	<Pause [amount]>
  This is simply the pauses inbetween words, I think it goes off of the amount frames, but I don't know...
  I typically use around 6-12 when pausing inbetween words.

 
	<Press A>
  Wherever you put this, the player will have to Press A to continue the dialogue.


	<Clear Text>
  Clears the text in currently shown, typically done after an <Press A> is used


	<End Conversation>
  Ends the current conversation.


	<Expression [Expression Name]>
  The Text Editor has a way of knowing whether the emotion you put in is right or wrong,
  and sometimes the editor changes the emotion to UNKNOWN 0x0000x when you save on that
  set of text, it should default to a emotion.

  ___

  # How to

Opening the File
  - Extract the forest_2nd.arc
  - Extract the message_data.bin from forest_2nd.arc
  - Extract the message_data_table.bin from forest_2nd.arc
    Make sure you put these files next to each other, it doesn't work for me when they are in seperate folders.
  - Open the Animal Crossing Text Editor
  - Select File, Open, then choose the message_data.bin file.
	There are a few other files you can open, but I don't know their signifigance.

Saving the File
- Select Save Text at the bottom right
- Select File, Save As
- Save the file in the same folder as the message_data_table.bin
  	Magic, its done
  
Using in game
- Replace message_data.bin with yours in forest_2nd.arc
- Replace message_data_table.bin with your new file in forest_2nd.arc
- Export the new forest_2nd.arc
- open the game's ISO
- replace forest_2nd.arc with the new exported one.
- export a new ISO
  	Boom bang pow, Luuji, you're the monster now :)
