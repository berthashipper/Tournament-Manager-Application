# Ping Pong Tournament Management System

## Overview
This Python program is designed to streamline the organization and management of ping pong tournaments. It allows users to input player names, assign matches, track scores, and maintain a leaderboard with real-time updates. The application leverages data structures, algorithms, and user interaction.

## Key Features

### Custom Player Input
- Users can create a personalized list of players for the tournament, securing a minimum of two players to start.
- The program checks for duplicates, guaranteeing a unique player roster.

### Match Assignment
- Matches are assigned automatically based on the number of games played by each player, ensuring fair play.
- Players are sorted by their game counts, ensuring that those who have played less frequently are prioritized for matches.

### Leaderboard Tracking
- The leaderboard updates and displays player statistics, including wins, losses, points, and total games played.
- This feature employs a dictionary data structure for efficient tracking of player performance.

### Dynamic Player Management
- Users can add or remove players mid-tournament, adjusting the active roster as needed.
- The program maintains a comprehensive list of all players, ensuring accurate record-keeping.

### Interactive Input
- The program prompts users for input to manage matches, winners, and scores, with error handling to enhance the user experience.
- Users can modify the player roster on the fly, allowing for greater flexibility during real-life tournament play.

### Ongoing Match Overview
- A live view of ongoing matches is provided, enabling easy score tracking and match completion.
- Players not currently engaged in a match are identified and can be quickly assigned to new matches.

## Technical Implementation

### Data Structures
- **Sets** are utilized for player management to ensure uniqueness.
- **Dictionaries** track leaderboard statistics, providing an efficient way to manage player performance data.

### Functions and Logic
- The program is modular, with specific functions handling player input, match assignment, score validation, and leaderboard updates.
- Input validation is implemented to enhance robustness and prevent errors/quitting during tournament management.

### Score Tracking and Leaderboard Updates
- The system updates scores and player statistics dynamically after each match.
- A sorted leaderboard is displayed at the end of the tournament, showcasing the final standings of all players.

## Potential Enhancements
- Future enhancements could include:
  - A web interface for easier access and management.
  - Database integration to persist tournament data across sessions.
  - Advanced analytics to evaluate player performance trends over time.

## Usage
1. Clone the repository or download the script.
2. Run the script in a Python environment.
3. Follow the prompts to enter player names, manage matches, and track scores.
