# MINESWEEPER 2025

A modern console version of Minesweeper with levels, statistics, and multilingual support.

## Features
- Play through 100 levels with increasing difficulty
- Save and load your game progress
- Top 5 leaderboard
- Statistics tracking (games played, won, lost, average level)
- Multiple languages (English, German, Polish, Ukrainian, French, Spanish)
- Light and dark theme

## Controls
- W/A/S/D or arrow keys: Move cursor
- Enter: Reveal cell
- F: Flag cell
- H: Show help
- Esc: Return to menu
- U: Save game
- L: Load game

## How to change language
Go to the main menu, select 'Language', and choose your preferred language. The app will remember your choice.

## How to run
1. Open the solution in Visual Studio or run with `dotnet run`.
2. Play directly in the console window.

## Technical Overview & Coding Practices

### Technologies Used
- **C# 12.0**: Latest language features for concise and modern code
- **.NET 8**: Fast, cross-platform runtime
- **System.Text.Json**: Efficient serialization for settings, saves, and stats
- **Console API**: For interactive UI and color output
- **LINQ**: For sorting, filtering, and manipulating collections
- **File I/O**: Persistent storage for saves, settings, stats, and leaderboard

### Coding Practices
- **Separation of concerns**: Game logic (Minefield) and UI (Program) are separated
- **Strong typing**: Use of enums, classes, and properties for clarity and safety
- **Multilingual support**: Dictionary-based text resources for easy localization
- **User settings persistence**: Language and theme saved in JSON for user convenience
- **Unit tests**: (see ConsoleApp3.Tests) for Minefield logic
- **Error handling**: Checks for file existence and valid data
- **Modern C# features**: Object initializers, pattern matching, interpolated strings
- **Code readability**: Consistent formatting, meaningful names, and comments

### How to Contribute
- Fork the repository on GitHub
- Use pull requests for changes
- Follow .NET and C# best practices
- Write unit tests for new features

## Author & License
Created by DevBrain © www.devbrain.cz
MIT License
