# Scrapland Reverse Engineering Project (ReScrap)

[<img src="https://github.com/user-attachments/assets/7bccd2cf-0236-4c18-b07b-cc5d642ca3dd" width="500">](https://github.com/ReScrap/level_viewer)

This the purpose of this Organization is to coordinate efforts towards bulding modding tools for American McGee's Scrapland (developed by MercurySteam) to allow for the creation of User Generated Content, that includes:

- Importers and Exporters for the 3D-Model and animation formats of Maps, Objects, Vehicles and Characters
- Documenting the Python Scripting Interface
- Documenting how the Game Engine works
- Documenting the Multiplayer network Protocol to allow for the creation of cross-platform dedicated server software, bots and utilities like a match Replay system and Online leaderboard
- Build tools to make modifying the game more accessible (Ideally a one-stop-shop solution built on top of Blender, but maybe it will end up being a Web application or a standalone porgram)
- And most importantly: to have fun

## Useful Resources

- [Notes](https://github.com/ReScrap/Notes) on Engine internals, file formats, etc
- [ScrapHacks](https://github.com/ReScrap/ScrapHacks): Kitchen sink repo for file format parsers, network sniffers, tools to poke at the game as it runs, etc
- [Scrap-Packed-Explorer](https://github.com/ReScrap/Scrap-Packed-Explorer) GUI and CLI to extract and modify the game's .packed files, developed by [@romibi](https://github.com/romibi) and [@Strongleong](https://github.com/Strongleong)
- [Localizer](https://github.com/ReScrap/Localizer) tool for decoding and encoding the game's language files to make it easier to fix translations (by [@Strongleong](https://github.com/Strongleong))

## Ghidra Project

a Ghidra project server is available, access is managed through [Tailscale](https://tailscale.com/), after being added to the GitHub org log in to the tailscale website using your GitHub account

![image](https://github.com/user-attachments/assets/a4000677-95f4-4bbf-91f8-99f31bc71f42)

![image](https://github.com/user-attachments/assets/b4068ce8-c212-4e52-85f3-c60c748a396f)

then pick **rescrap.org.github** when asked to select a network

![image](https://github.com/user-attachments/assets/b1bb3898-852f-4558-a66f-79ef252142f7)

after your account has been approved you should be able to connect to the Ghidra server under the hostname `ghidra`, port 13100

