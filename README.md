# PacMon
C++ Project using SFML

1. Go to https://www.sfml-dev.org/download.php.
2. Download the latest sfml version based on your OS.
3. Add the frameworks, include files, and lib files from SFML to your machine, or you can add them while compiling the code.
5. I have installed it using homebrew in MacOS and it get saved on opt/homebrew/Cellar/sfml/2.6.0
6. For (#include <SFML/Graphics.hpp>) I added -I/opt/homebrew/Cellar/sfml/2.6.0/include
7. To run the code we also need SFML libraries -L/opt/homebrew/Cellar/sfml/2.6.0/lib
8. Command to run the code:
    clang++ *.cpp -std=c++17 -I/opt/homebrew/Cellar/sfml/2.6.0/include -o pacman -L/opt/homebrew/Cellar/sfml/2.6.0/lib -lsfml-graphics -lsfml-window -lsfml-system
9. I have used W,A,S,D to play the game.
10. For MacOS users enable Input Monitoring in Privacy and Security to enable keyboard for VScode or terminal.
