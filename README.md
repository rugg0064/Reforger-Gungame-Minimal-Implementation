# Reforger-Gungame

A playable implementation of the Gungame mod for Arma Reforger.

## How to set up

### Workbench Editor

1. Clone this repo into any directory
2. This mod relies on it's gamemode [https://github.com/rugg0064/Reforger-Gungame](https://github.com/rugg0064/Reforger-Gungame), clone it to the same directory as this project
3. Open Arma Reforger Tools
4. Click "Add Project" -> Scan for Projects, select the directory containing the projects
5. Open GungameImplementationMinimal

### In game play

1. Subscribe to this addon and the game mode from the reforger workshop

- https://reforger.armaplatform.com/workshop/604E5A887DC76562-GunGame-MinimalScenario
- https://reforger.armaplatform.com/workshop/604C30B1720985A9-GunGame-Base

2. From the game's main menu, go to scenarios, play "Gungame"

### Hosting a dedicated server

1. Use [official resource](https://community.bistudio.com/wiki/Arma_Reforger:Server_Hosting) to get a dedicated server running
2. Set up your server configuration json file with the following fragment

```
{
  "game": {
    "scenarioId": "{843F1D5DEFA6A7C3}Missions/GungameMinimal.conf",
    "mods": [
      {
        "modId": "604C30B1720985A9",
        "name": "Gun Game - Base"
      },
      {
        "modId": "604E5A887DC76562",
        "name": "Gun Game - Minimal Scenario"
      }
    ]
  },
}
```

# Issues

If you encounter any issues or have suggestions for improvements, please open an issue on the Issues page. Provide as much detail as possible, including steps to reproduce the issue.

# License

This mod is open-source and distributed under the MIT License.
