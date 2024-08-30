# Step 1: Create the README.md file with the content
echo "# Tic-Tac-Toe Java

## Overview
This is a simple command-line-based Tic-Tac-Toe game implemented in Java. The game allows two players to play against each other in a 3x3 grid.

## Features
- Two-player mode
- Basic Tic-Tac-Toe rules
- Command-line interface

## Installation
1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/arvind621/TicTacToe-java.git
   \`\`\`
2. Compile the Java file:
   \`\`\`bash
   javac TicTacToe.java
   \`\`\`
3. Run the application:
   \`\`\`bash
   java TicTacToe
   \`\`\`

## Usage
After running the application, follow the on-screen instructions to play the game.

## Contributing
Feel free to submit issues or pull requests for improvements!

## License
This project is open source and available under the MIT License.
" > README.md

# Step 2: Stage the README.md file
git add README.md

# Step 3: Commit the README.md file
git commit -m "Add README.md file"

# Step 4: Push the changes to GitHub
git push origin master
