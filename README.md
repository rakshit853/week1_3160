# week1_3160
# Cricket Team Manager

This is a simple C++ program for managing a cricket team. The program allows you to add players, display player details, and manage the team.

<hr>

## Features

- Add new players to the team
- Display details of all players
- Display details of a specific player by name

<hr>

## Getting Started

Follow these instructions to run the program on your local machine.

### Prerequisites

You need to have a C++ compiler installed on your machine. You can use g++, which is part of the GNU Compiler Collection.

### Running the Program

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cricket-team-manager.git
    ```
    <br>

2. Navigate to the project directory:
    ```bash
    cd cricket-team-manager
    ```
    <br>

3. Compile the program:
    ```bash
    g++ main.cpp -o CricketTeamManager
    ```
    <br>

4. Run the program:
    ```bash
    ./CricketTeamManager
    ```

<hr>

## Code Explanation

### Player Class

This class represents a player with the following attributes:
- `name`: The name of the player
- `age`: The age of the player
- `role`: The role of the player (e.g., Batsman, Bowler)
- `matches`: The number of matches played by the player
- `runs`: The number of runs scored by the player
- `wickets`: The number of wickets taken by the player

### CricketTeamManager Class

This class manages the cricket team with the following methods:
- `addPlayer(const Player& player)`: Adds a player to the team
- `displayPlayers()`: Displays all players in the team
- `displayPlayerByName(const std::string& name)`: Displays details of a player by their name

### Main Function

The main function demonstrates how to use the `CricketTeamManager` class by:
- Adding sample players
- Displaying details of all players
- Displaying details of a specific player by name

<hr>

## Sample Output

