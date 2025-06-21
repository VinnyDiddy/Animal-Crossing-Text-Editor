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
- Boom bang pow, Luuji, you're the monster now :)

# An Example
	Hey,<Pause [5]> friend.<Press A>
	Finaly moving out,<Pause [6]> huh?<Pause [15]>
	Gonna<Pause [4]> get your own place and<Pause [4]>
	see the world?<Press A>
	<Clear Text>That's real groovy, friend.<Press A>
	Who needs someone<Pause [4]> telling you
	what you<Pause [4]> can and<Pause [4]> can't
	do<Pause [4]> all the time.<Press A>
	<Clear Text>You can do<Pause [6]>
	what<Pause [6]> you want,<Pause [6]>
	when<Pause [6]> you want,<Pause [6]>
	wherever<Pause [6]> you want.<Press A>
	<Clear Text>Yeah, being free like that,
	it's all rea<Pause [4]>a<Pause [4]>a<Pause [4]>l<Pause [4]>l<Pause [4]>y groo<Pause [4]>o<Pause [4]>o<Pause [4]>vy.<Press A>
	<Clear Text>But livin' on your own<Pause [6]>
	is such a drag,<Pause [6]> too.<Press A>
	Some say<Pause [4]> it gets<Pause [4]> really
	blue out there.<Pause [4]>.<Pause [4]>.<Pause [4]><Press A>
	<Clear Text>But,<Pause [4]> if you've got some
	tight friends<Pause [4]> to chill out with,<Pause [4]>
	then it'll all work out<Pause [4]>
	seamlessly.<Press A>
	<Clear Text>So... I guess I can
	finally ask you this.<Pause [4]>.<Pause [4]>.<Pause [4]>
	Are you ready to ride the rails?<Press A>
	<Clear Text>Well<Pause [4]> I've forgotten how to<Pause [4]> add the
	question into the menu, so<Pause [4]>.<Pause [4]>.<Pause [4]>.<Pause [4]>
	I'm just gonna end the<Pause [4]>
	conversation<Pause [4]> now.<Press A>
	<Clear Text>Catch ya later, friend.<Press A>
	<Clear Text>Nevermind, I'll steal it
	from the same file by
	copying the text I created...<Press A>
	<Clear Text>Clicking on the searched
	file on the search list.<Press A>
	<Clear Text>Selecting the text I don't
	want anymore, or the text I'm
	changing up.<Press A>
	<Clear Text>Of course, without
	removing the Set 2 Choices thing.<Press A>
	<Clear Text>Then pasting this text
	onto it! Yipee!<Press A>
	So.<Pause [6]>.<Pause [6]>.<Pause [6]>
	Let me ask you<Pause [6]> one<Pause [6]> more<Pause [6]> time.<Press A>
	<Clear Text><Expression [Wondering (K.K.)]>Are you ready to ride the
	rails and go on a new
	adventure?<Set 2 Choices [006E] [006F]><Press A><Open Choice Selection Menu><Choice #1 MessageId [09C9]><Choice #2 MessageId [09DB]><Force Dialog Switch>
	<Continue to Next Dialog>
 For those looking for the entry, its Entry 9C7 offset 73FA2
