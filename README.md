# TICS Chat Color Picker

A web-based color picker tool for the **Total Immersive Chat System (TICS)** mod in Project Zomboid.

## Features

- **Live Preview**: See how your colors look in a simulated chat window
- **Color Picker UI**: Click any color to open a visual color selector
- **All Chat Channels**: Customize colors for whisper, low, say, yell, me, do, ooc, pm, faction, safehouse, general, and admin
- **Text Formatting**: Set colors for dialogue (quotes), italics, and bold text
- **One-Click Copy**: Copy individual commands or all commands at once
- **Configurable Background**: Adjust the chat preview background color and opacity

## Usage

1. Open `index.html` in your browser (or visit the GitHub Pages link)
2. Click on any color swatch to open the color picker
3. Adjust colors and see the live preview update
4. Click "Copy" next to any setting to copy that command
5. Click "Copy All Commands" to copy everything at once
6. Paste the commands in Project Zomboid chat

## Chat Commands Reference

| Command | Description | Example |
|---------|-------------|---------|
| `/color` | Your name color | `/color 255,255,255` |
| `/emotecolor` | Chat stream color | `/emotecolor me 255,255,255` |
| `/dc` | Dialogue color (text in quotes) | `/dc 255,255,255` |
| `/ic` | Italics color (*text*) | `/ic 255,255,255` |
| `/bc` | Bold color (**text**) | `/bc 255,255,255` |

## Live Demo

Visit: https://pcloadletter05.github.io/zb_chat_colors/

## Local Usage

Simply download `index.html` and open it in any modern web browser. No server required.

## Related

- [Total Immersive Chat System](https://steamcommunity.com/sharedfiles/filedetails/?id=3621658789) - The Project Zomboid mod this tool is designed for
