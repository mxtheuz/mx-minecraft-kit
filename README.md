# Mx Kit Plugin

## About the Plugin

The `MxKit` plugin is a Bukkit plugin developed by mxtheuz, aimed at enhancing the gameplay experience on Minecraft servers. It provides various commands and permissions that grant players access to different kits based on their roles, such as "dono," "admin," and "moderador." Additionally, the plugin includes a VIP system with custom abilities, allowing server administrators to manage player permissions effectively.

## Features

- Group-based Kits: The plugin offers kits for different player roles, such as "dono," "admin," and "moderador," containing specific items and abilities to enhance gameplay.
- VIP System: Players can be granted VIP status with unique abilities, such as increased speed or PvP privileges, using the `/vip` command.
- Permission Management: The plugin allows server administrators to grant or revoke permissions for individual players using the `/perm` and `/unperm` commands.
- Event Handling: The plugin efficiently handles player events, such as joining the server, through the `PlayerJoinEvent` and custom `PlayerManager` event handlers.

## Installation

To install the `MxKit` plugin, follow these steps:

1. Download the latest version of the plugin JAR file from the [Releases](https://github.com/mxtheuz/mx-minecraft-kit/releases) page.
2. Place the downloaded JAR file into the `plugins` folder of your Bukkit server.
3. Restart your Minecraft server to load the plugin.

## Commands and Permissions

- `/dono`: Grants "dono" players special items and abilities.
- `/admin`: Provides "admin" players with admin-level items and permissions.
- `/moderador`: Equips "moderador" players with specific items and abilities.
- `/perm <player> <permission>`: Grants a specified permission to a player. (OP-only)
- `/unperm <player> <permission>`: Revokes a specified permission from a player. (OP-only)
- `/kit`: Provides players with kits based on their roles and permissions.
- `/vip <player> <type>`: Grants VIP status to a player with specific abilities. (OP-only)
- `/unvip <player> <type>`: Removes VIP status and abilities from a player. (OP-only)

## License

The `MxKit` plugin is released under the [MIT License](https://github.com/mxtheuz/mx-minecraft-kit/blob/master/LICENSE), allowing users to freely use and modify the plugin in accordance with the terms of the license.

## Contributing

Contributions to the `MxKit` plugin are welcome! If you encounter issues or have suggestions for improvements, please [create an issue](https://github.com/mxtheuz/mx-minecraft-kit/issues) or [submit a pull request](https://github.com/mxtheuz/MxKit/pulls). Follow the [Contributing Guidelines](https://github.com/mxtheuz/mx-minecraft-kit/blob/master/CONTRIBUTING.md) before making contributions.

## Support

For any assistance or queries related to the `MxKit` plugin, feel free to [open an issue](https://github.com/mxtheuz/mx-minecraft-kit/issues) on the GitHub repository.

## Credits

The `MxKit` plugin was developed by [mxtheuz](https://github.com/mxtheuz), and contributions from the Bukkit community are greatly appreciated.

---
