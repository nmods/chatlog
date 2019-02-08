# Chatlog

Chatlog module for Tera proxy

### config file
By default it logs chat in 4 files, change config to suit your needs.
- `fileName` can be anything
- `channels` is a string array of channels you want logged in this file
  - valid channels:
    - `say`, `party`, `guild`, `area`, `trade`, `greet`, `bargain`, `lfg`, `partynotice`, `system`, `raidnotice`, `emote`, `global`, `raid`, `greetings`, `megaphone`, `guildad`, `whisper`, `private`
You can even change the format of messages
Default path for chatlogs is `proxy/log`