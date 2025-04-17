# Weather and Blackout Script for ESX

This script allows server admins to control the weather and toggle a blackout effect in-game. It's designed for **ESX-based** servers and provides simple commands for changing the weather, time of day, and simulating power outages.

## Features

- **Weather Control**: Admins can change the weather to various types, including clear skies, rain, snow, and more.
- **Time Control**: Set the time of day to **day** or **night**.
- **Blackout Mode**: Toggle a **blackout** effect across the server, simulating a power outage.
- **Admin-only Access**: Only admins can use these commands to modify the game environment.

## Commands

### `/weather [type] [day|night]`

- **[type]**: Weather type (choose from `EXTRASUNNY`, `CLEAR`, `SMOG`, `FOGGY`, `RAIN`, `SNOW`, etc.).
- **[day|night]**: Set the time to **day** or **night**. This is optional.

Example:
This will change the weather to rain and set the time to night.

### `/blackout [on|off]`

- **[on|off]**: Turn the blackout effect **on** or **off**.

Example:
This will activate the blackout, turning off lights for all players.

## Installation

1. **Download the Script**: Place the script folder in the `resources` directory of your server.
2. **Update `server.cfg`**: Add `start wetter_script` to your `server.cfg` to ensure the script is loaded.
3. **ESX Setup**: Ensure that **ESX Legacy** and `es_extended` are installed and running.
4. **Restart the Server**: Restart the server to load the new resource.

## Requirements

- **ESX Legacy** (with `es_extended`).
- Server admin permissions to execute the commands.

## License

This script is released under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this script, as long as you retain the original copyright and license text.

---

## Contribution

If you want to contribute or suggest improvements to the script, feel free to open an issue or submit a pull request.

---

### Changelog

- **v1.0.0**: Initial release with weather and blackout commands.

