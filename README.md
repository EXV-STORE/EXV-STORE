# exv-firstpersonaim

This resource is a FiveM script for QBCore that forces the player to aim in first-person view, while returning to third-person view when not aiming.

**Features:**
- Automatically switches to first-person view while aiming.
- Restores third-person view after releasing the aim button.
- Lightweight script with minimal performance impact.
- Customizable via configuration options.
- Uses 0.00ms on idle and 0.01ms~ while in use.

## Installation

1. **Download** the script from the repository.
2. **Place** the script in your `resources` directory.
3. **Add** the following lines to your `server.cfg` to ensure the script is running:
    ```
    ensure exv-firstpersonaim
    ```

## Configuration

You can modify the configuration file to adjust the behavior of the script. Below are the available options:

- `Config.checkForUpdates` (boolean): Set to `true` if you want the script to automatically check for updates.
- `Config.EnableFirstPersonAim` (boolean): Set to `true` to enable first-person view when aiming.

## Preview

You can check out a video demonstration of this script here: *(Add video link if applicable)*

## Extra Information

- The script works out-of-the-box with QBCore.
- It ensures minimal performance impact with no noticeable delays.

## Support

For help, bug reports, or to contribute, please join our Discord:

[![Discord](https://cdn.discordapp.com/attachments/840810737298702406/1286783581934456923/PRywUXcqg0v5DD6s7C3LyQ.png?ex=66ef2a19&is=66edd899&hm=66486c1bdbaa6b92bf0e2a012496a979531249b21a092cdc2cc5156aab4ab678&)](https://discord.gg/q9ECc4TCpD)

## Updates

This script checks for updates automatically (if configured). You will be notified in the console when a new version is available.
