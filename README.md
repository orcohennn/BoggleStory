# Boogle Story
Boggle is a hilarious word-making game that requires exceptional vocabulary
Players will have three minutes to create as many words as possible from a few
jumbled-up letters.
Try to create long words with more letters to score more points.
At the end of the game, the person with the highest score will win!
Length: 3 minutes


<img src="Readmepics/mainscreen.png" alt="Description of Image" width="600" height="300">
# Boogle Story Gameplay
<img src="Readmepics/ingame.png" alt="Description of Image" width="600" height="600">
# Installation
Clone this repository: git clone https://github.com/your-username/boogle-story.git
Install the required libraries: pip install -r requirements.txt
Usage
To start playing Boogle Story, run the following command in your terminal:

css
Copy code
python main.py
Rules
The game is played on a 5x5 grid of randomly generated letters. Players have to form words by connecting adjacent letters horizontally, vertically, or diagonally. The game ends after a fixed amount of time, and players earn points for each valid word they find. The longer the word, the more points they earn.

# Libraries Used
Pygame: for game development and user interface
PyDictionary: for checking word validity
Time: for timing the game
Credits
This project was developed by Your Name as a personal project.

# License
This project is licensed under the MIT License.

# Code Example
Here is a sample code snippet for generating the game grid:

python
Copy code
import random

# generate a 5x5 grid of letters
letters = ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
grid_size = 5
grid = [[random.choice(letters) for j in range(grid_size)] for i in range(grid_size)]
print(grid)
Screenshots
Include screenshots of your game in action!
