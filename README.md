# Template Plugin for Spigot and CraftBukkit Servers

## Version: 1.20.X

### Description:
This plugin allows for easy customization of player welcome messages by modifying a config file. Additionally, it provides commands for reloading the plugin configuration and responding to custom commands.

### Features:
- **Player Welcome Customization**: Change the suffix of player welcome messages to greet players uniquely.
- **Config Reload Command**: Reload the plugin's configuration without restarting the server.
- **TellMe Command**: Respond to custom commands from players with specific messages.

### Usage:
1. **Configuring Player Welcome Message**:
    - Open the `config.yml` file located in the plugin's source code.
    - Modify the `suffix` value to customize the player welcome message.

2. **Reloading Plugin Configuration**:
    - Use the `/reloadtp` command to reload the plugin's configuration.

3. **Using Custom Commands**:
    - Utilize the `/tellme <message>` command to have the server respond with a specific message.

### Installation:
1. Download the latest version of the plugin from the releases section.
2. Place the downloaded `.jar` file into your server's `plugins` folder.
3. Restart or reload your server to enable the plugin.

### Example Configuration (config.yml):
```yaml
suffix: "[TEMPLATE-PLUGIN]"
