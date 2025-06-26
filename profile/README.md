# SikaUI

![Banner](https://i.postimg.cc/05LM1bYD/e0a4f47f-0736-4eee-9791-425172eba9ba.png)

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Release](https://img.shields.io/badge/release-2025-green)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)
![Roblox](https://img.shields.io/badge/engine-Roblox-red)

**SikaUI** is a modern, lightweight UI library for Roblox Lua scripting, designed to streamline creating immersive game interfaces. Optimized for Windows systems and 2025 Roblox updates.

## Features

- 🚀 **High Performance**: Minimal lag with optimized rendering
- 🎨 **Customizable Themes**: Prebuilt dark/light modes + custom styling
- 🖱️ **Intuitive API**: Simple syntax for rapid UI development
- 📱 **Responsive Design**: Adapts to all screen resolutions
- 🔒 **Secure**: Sanitized input handling

## Installation

1. Download `SikaUI.rbxm` from Releases
2. Drag into Roblox Studio
3. Require the module:
```lua
local SikaUI = require(path.to.SikaUI)
```

## Quick Start

```lua
-- Create a new frame
local frame = SikaUI.new("Frame", {
    Size = UDim2.new(0, 200, 0, 150),
    Position = UDim2.new(0.5, 0, 0.5, 0),
    Theme = "Dark"
})

-- Add interactive button
frame:Button("ClickMe", function()
    print("Button pressed!")
end)
```

## Documentation

| Component    | Description                          |
|-------------|--------------------------------------|
| `Frame`     | Container for UI elements           |
| `Button`    | Interactive clickable element       |
| `Slider`    | Adjustable value selector           |
| `Textbox`   | User input field                     |

## Support

For bug reports or feature requests, open an Issue. Pull requests welcome!

![Lua](https://img.shields.io/badge/Lua-2C2D72?logo=lua&logoColor=white)
![Roblox Studio](https://img.shields.io/badge/Roblox_Studio-00A2FF?logo=roblox&logoColor=white)
