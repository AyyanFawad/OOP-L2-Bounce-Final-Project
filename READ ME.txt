- After extracting this folder, rename the vscode folder to .vscode
- Open this folder in VSCode
- Open Game.hpp and GameObject.hpp and change the #include "SDL2/SDL.h" and #include "SDL2/SDL.h" to #include "SDL.h" and #include "SDL.h" if you are on windows
- No changes needed if on mac

- Open VSCode terminal and put this command to compile everything:

	g++ *.cpp -IC:\mingw_dev_lib\include\SDL2 -LC:\mingw_dev_lib\lib -w -lmingw32 -lSDL2main -lSDL2 -lSDL2_image

- On windows, run the game by this command:
	
	.\a.exe
- On mac, run the game by this command:
        .\a.out
	
How to play:
 - Arrow keys are used to control the ball
 - reach the ring to win the game
 - the diamond provides you with extra jumping capabilties
 - spikes will remove a life from you
