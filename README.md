# DUST Optimizer

DUST is a lightweight optimizer for Roblox that improves performance by managing CPU and memory usage. It adjusts process priorities and affinities based on whether a Roblox window is active or running in the background. This is not a cheat and does not risk bans.

## Features

- Reduces CPU and RAM usage for Roblox when unfocused  
- Increases CPU priority and core affinity for the active Roblox window  
- Helps improve FPS and overall system responsiveness  
- Suitable for all types of users

## Usage

### For Users

1. Download the latest release from the Releases section.  
2. Run `ScheduledTaskInstaller.bat` to install DUST as a startup service called "DUST Agent".  
3. To remove DUST, run `Uninstall.bat`.

### For Developers

1. Open the project in Visual Studio.  
2. Build in Debug mode for testing or Release mode for production.  
3. Make sure `DUST.exe` is in the same folder as the batch files.