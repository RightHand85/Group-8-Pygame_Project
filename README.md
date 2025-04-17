You are free to create an original game or implement a game that already exists.  Your game can be a puzzle game or any other type of game.

What you submit must be fully written in Python by one or more members of your team.  It must use the Pygame module and it must not contain any libraries that aren’t part of Pygame or the Python standard library.  

In addition you:

Must use at least 10 different Surface objects.
Only objects which are blitted and visible in the Display Surface count
The Display’s Surface (retrieved using set_mode()) counts as a Surface object
It must access at least 5 different files, for either reading or writing.
Opening a file isn’t enough: Files being read must change the state of the game; files being written to must have their content be based on the state of the game.
Files containing code or similar (e.g: DLLs) do not count towards this requirement
It must play at least 2 different sounds.
If the sounds come from files on disk, they also count towards the requirement.
It must take inputs from either the keyboard, mouse, or a controller.
It must feature some sort of movement (i.e.: surfaces moving across other surfaces)
In general, Surface A is said to be moving across Surface B if:
Surface A is blitted onto Surface B at different locations between frames
There is overlap in the area of where Surface A was previously blitted and where it will be blitted next
Consult your professor if you are unsure if something constitutes movement
The user must be able to quit the game without pressing the X button at the top right or stopping the project that runs the game.
There must be a way for the game to “end”.
If the game is some sort of puzzle, the puzzle must be solvable and the game must acknowledge that the puzzle has been solved.
If the game has win and lose conditions, these must be implemented.
Either of the above must close the game or allow the user to restart it.
Game instructions must be present within the game using correct English.
Game must not crash or stall.
Calling pygame.time.delay() or pygame.time.wait() will usually cause the game to stall and should be avoided.
Game must show no obvious flaws, such as dropped inputs or rogue Surfaces.
