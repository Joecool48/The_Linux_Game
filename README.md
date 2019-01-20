# The Linux Game
A file system stat searching game for Linux

This script controls the functionality of the Linux Game.

### Note
* Script creates file system with breadth in mind more than depth
* Script generates random newline seperated words in each file
* Script gives file and directory names random word titles as well
* Each instance has an json cache to store game info, and the answers are hashed with sha256 to prevent cheating
* Games are referenced by their names for deleting, checking, and creating

#### Create
To create a new game instance use `./linux_game.py create --name  *create_game_name*
Use `./linux_game.py create --help` for more command info

#### Delete
To delete a game instance simply use `./linux_game.py create --name *delete_game_name*`

#### Check
To check your answers simply user `./linux_game.py check --name *created_game_name*`

* You can cntl-c at any time, and it will save your progress
* Questions are answered sequentially, and cannot be skipped
* After you answer all the questions you must create a new game in order to play again
* You have infinite attempts
