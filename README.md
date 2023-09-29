# PacMon
C++ Project using SFML

Step 1. Go to https://www.sfml-dev.org/download.php.

Step 2. Download the latest SFML version based on your OS.

Step 3. Add the frameworks, include files, and lib files from SFML to your machine,or you can add them while compiling the code just like I did.

Step 4. I have installed it using homebrew in MacOS and it get saved on opt/homebrew/Cellar/sfml/2.6.0

Step 5. cd source_code and then run the command on step 8 (replace clang with g++ and opt/homebrew/Cellar/sfml/2.6.0/ with director where SFML is installed)

Step 6. For (#include <SFML/Graphics.hpp>) I added -I/opt/homebrew/Cellar/sfml/2.6.0/include

Step7. To run the code we also need SFML libraries -L/opt/homebrew/Cellar/sfml/2.6.0/lib

Step 8. Command to run the code:
 clang++ *.cpp -std=c++17 -I/opt/homebrew/Cellar/sfml/2.6.0/include -L/opt/homebrew/Cellar/sfml/2.6.0/lib -lsfml-graphics -lsfml-window -lsfml-system -o pacMon
 
Step 9. I have used W,A,S,D to play the game.

Step 10. For MacOS enable Input Monitoring in Privacy and Security to enable keyboard for VScode or terminal.

