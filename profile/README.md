# Scrapland Reverse Engineering Project (SREP)

This the purpose of this Organization is to coordinate efforts towards bulding modding tools for American McGee's Scrapland (developed by MercurySteam) to allow for the creation of User Generated Content, that includes:

- Importers and Exporters for the 3D-Model and animation formats of Maps and Characters
- Documenting the Python Scripting Interface
- Documenting how the Game Engine works
- Documenting the Multiplayer network Protocol to allow for the creation of cross-platform dedicated server software, bots and utilities like a match Replay system and Online leaderboard
- Build tools to make modifying the game more accessible (Ideally a one-stop-shop solution built on top of Blender, but maybe it will end up being a Web application or a standalone porgram)
- And most importantly: to have fun

## Useful Resources

- [Notes](https://github.com/Scrapland-Reverse-Engineering-Project/Notes) on Engine internals, file formats, etc
- [ScrapHacks](https://github.com/Scrapland-Reverse-Engineering-Project/ScrapHacks): Kitchen sink repo for file format parsers, network sniffers, tools to poke at the game as it runs, etc
- [Scrap-Packed-Explorer](https://github.com/Scrapland-Reverse-Engineering-Project/Scrap-Packed-Explorer) GUI and CLI to extract and modify the game's .packed files, developed by [@romibi](https://github.com/romibi) and [@Strongleong](https://github.com/Strongleong)

## Ghidra Project

a Ghidra project server is available, access is currently restricted by SSH key authorization, if you would like acces please contact [@Earthnuker](https://github.com/Earthnuker) to have an account created and your SSH key added.
once you have been whitelisted connect using either:

`ssh -v -N -L 13100:127.0.0.1:13100 -L 13101:127.0.0.1:13101 -L 13102:127.0.0.1:13102 ghidra@lsrv.spdns.org`

or by adding the following to `~/.ssh/config` and connecting with `ssh -N srep-ghidra`

```ssh-config
Host srep-ghidra
	HostName lsrv.spdns.org
	User ghidra
	LocalForward 13100 127.0.0.1:13100
	LocalForward 13101 127.0.0.1:13101
	LocalForward 13102 127.0.0.1:13102
```

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
