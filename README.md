# BingoCard

#SETUP

Put all the files in the same folder.
It should do this by default when downloading as a .zip.
you can open either of the .pd files and it should open processing with both the BingoCard class and Cell class.
There will be a line in BingoCard  -->    scanner = new Scanner(new File("Insert File Name Here"));
Delete the text inside the "".
Put the file location of the HorrorBingo.txt file.
Here is an example -->  C:\\Programming Stuff\\HorrorBingo.txt
So the changed line should look like this -->  scanner = new Scanner(new File("C:\\Programming Stuff\\HorrorBingo.txt"));
Next hit the play button at the top.
Should compile and display the bingo board.

#USING

You can click on the square to mark it.
You can mark it again to undo.
You can also press any key to save the sketch as a picture.
It will save in the same folder as the .pd file.
You should see txt that comes up saving saved in the termal at the bottom of processing.
If not make sure you are clicked into the sketch window.


#CHANGES

At the very end of the BingoCard file there isa method called void keyPressed.
The method should look like this:

void keyPressed(){
   save("HorrorBingoCard.png");
   println("saved");
   //exit();
  }
  
  You can change the line --> //exit(); to --> exit(); if you want the sketch to close after you save a picture.
  If you dont want to use the sketch and just the img then you can add this in.
