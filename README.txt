Features: This hangman program has different features such as animation, file read, and sound. 
	
Animation: Animation is written in assembly using the co-ordinates and by drawing lines and circles. Objects and body parts of the hangman is 
		   added respectively for every wrong character guesses. If the wrong guess exceeds 8 (or equal to 9), the man is hanged and eyes are 
 		   enlarged while being hanged. 

File Read: The program is provided with a dictinary file which contains the words separated by asterisk. Assebly code is written to read the file,
	   store the content of file to buffer and print the string. 

Sound: There are 4 types of sounds implemented in this program using basic syscalls. If the user input is incorrect, then the high note beep is played.
       When the input matches the character, one "tick" sound is played. If you guessed correctly, one clear and warming sound is played. If you guessed
       incorrectly long and high note annoying beep sound is played. 
				
						&

Limitation: Some of the features are limited on the MIPS assembly. The limitations of the program are listed below
	    1. Termination: Once the program is started, the user has to complete the whole loop to exit the game. Quit, pause/resume/stop isn't implemented.
            2. Words: The word on the program is only limited to the words which are saved on the dictionary file.
            3. Animation: The animation of the hangman is limited to bitmap display. We'll have to connect the bitmap display to mips to see the animation.