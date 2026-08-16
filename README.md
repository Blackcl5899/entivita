# EntiVita

A Fabric mod that displays the health of living entities as a numeric value alongside a heart icon above their heads.

## Features

- Displays current health points for players, mobs, and animals.
- Renders a heart texture next to the health number.
- Health updates in real-time as entities take damage or heal.
- Adjustable display scale and colors via an in-game configuration screen.
- Option to toggle the display on or off.

## Installation

1. Download the latest .jar file from the releases page.
2. Place the .jar file into your Minecraft mods folder.
3. Ensure you have Fabric Loader installed for your Minecraft version.
4. Launch the game.

## Configuration

You can configure EntiVita through the in-game settings menu:

- Press the default keybind (O) to open the configuration screen.
- Toggle the health display on or off.
- Toggle the entity name display on or off.
- Adjust the display scale (from 50% to 200%).
- Change the heart color.
- Change the text color.

Alternatively, you can edit the `config/entivita.json` file manually.

## Usage

Once installed, simply look at any living entity (player, zombie, cow, etc.). A heart icon and the entity's current health will appear floating above their head.

## Building from Source

To build the mod from source, you need Java 17 or higher and Gradle.

1. Clone the repository.
2. Open a terminal in the project directory.
3. Run the following command:
   
   ./gradlew clean build
   
4. The built .jar file will be located in the `build/libs/` directory.

## Dependencies

- Minecraft (Java Edition 1.20.1 or later)
- Fabric Loader (0.14.0 or later)
- Fabric API (optional, but recommended)

## License

This project is licensed under the MIT License. See the LICENSE file for details.
