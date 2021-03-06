# Installation
If you are using Windows or Mac, download the corresponding zip, then unzip it.

If you are on Windows, you will extract an executable and some .dll files into a folder, then you can run the executable.

If you are on Mac, you will find a .app file inside the zip which you can execute.

If you are on Linux, download AdelieTAS.love and install the [official LÖVE packages](https://www.love2d.org), which will then let you run the .love file.

# Usage
First of all, you will see a timer in the top-left corner, which tracks the time, and a black rectangle right next to it, the black rectangle is an input viewer, where you can see what keys are being pressed on that frame. The input viewer will be blacked out because you can't input anything yet, as you are in the spawning state, once the spawning state is over (at 00:01.16) you will be able to see the keys.

Each time you press a key (up, down, right, left, x, c, or z) that key will toggle on/off for that frame.

To step forward in time press L, which will advance the game one frame, and the keys that were inputted for that frame will be executed.

To step backwards in time press K, which will step 1 frame backwards, and you can change what was pressed before.

To see the TAS in real time press P, which will start reproducing the inputs from the frame you are currently on. (Note: you shouldn't input anything while the TAS is reproducing)

To go back to the first frame press D, which will restart the game but still keep your inputs.

To save the TAS press M, which will automatically create a file called 'adelie.tas' in the love2d folder (check the [love2d page](https://love2d.org/wiki/love.filesystem) for more information).

To open a TAS file, simply drag the file into the window, note that this won't change the current state of the game, so you should always go back to the start after loading a TAS file.

Press Y to see the current position, rem values (sub-pixels) and speed of the player on the console.

You can press F1 or F6 to save a screenshot, F3 or F8 to start a recording and F4 or F9 to save the recording, both saved to the love2d folder.
