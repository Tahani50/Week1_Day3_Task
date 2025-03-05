# Teams & Players SwiftUI App

## Description
This is a SwiftUI app that displays a list of teams and their players. It categorizes teams into three types: **National**, **Club**, and **Academy**.

## Features
- Uses a `Player` struct to define individual players.
- Uses a `Team` class to define teams and their associated players.
- Implements an `enum` (`TeamType`) to differentiate between National, Club, and Academy teams.
- Uses an `ObservableObject` (`TeamViewModel`) to manage and update the list of teams and players.
- Displays teams and players using `List` and `Section` in SwiftUI.

## How It Works
1. **Data Definition:**
   - The `Player.swift` file defines the `Player` struct.
   - The `Team.swift` file defines the `Team` class, including an array of `Player` objects.
   - The `ViewModel.swift` file contains the `ViewModel` class, which stores and manages the list of teams.

2. **Displaying Data:**
   - The `ContentView.swift` file fetches data from `ViewModel` and displays it in a `List`.
   - Teams are grouped into sections based on their type (National, Club, Academy).
   - Each team section lists its players along with their position.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url.git
   ```
2. Open the project in Xcode.
3. Run the app using the iOS simulator.

## Future Enhancements
- Add functionality to dynamically add or remove players.
- Implement a detailed view for each player.


