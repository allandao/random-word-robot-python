# Random Word and Robot Generator
The goal of this project is to generate a random word with the definition, using robohash to generate a random robot for the generated word. 

The file ```dictionary_robot.py``` is meant to be run in the command line.
The end goal of this project is to implement the script on PythonAnywhere's scheduled task system to schedule the script running each day. Alongside what ```dictionary_robot.py``` does, the script run daily will also email the results to a personal email.

Using https://random-word-api.herokuapp.com/home for requesting random words, the (unofficial) Google Dictionary API at https://dictionaryapi.dev/ for definitions, and robohash for uniquely generated robots at https://robohash.org/.

## Running the script
To run this project, download the files and navigate to the project files.
1. Open a terminal or command prompt window
2. ```cd``` into the root folder
3. Run ```source ./env/bin/activate```
4. Check for (env) to confirm that the Python environment (with all required packages) has properly loaded in 
5. Run ```python3 dictionary_robot.py``` to run the Python file

## Terminal Version
The following image shows an example of what the output of this program may be.
![alt text](terminal_output.png)
The following image shows an example of what the random robot that robohash has generated based on the random word that was received from the api.
![alt text](bargaining.png)
