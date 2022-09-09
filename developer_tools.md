# Enable Chrome Developer tools in Discord Desktop App

1. Close Discord
2. Open `%appdata%/discord/settings.json`
3. Add the following line
   ```"DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true```
4. Lauch Discord and you will be able to open Developer tools using the keybind. (Ctrl + Shift + I)

Things to consider:
- Don't paste things in the console that other people send you. Such things can compromise your account, and even your computer.
- Don't screenshare or send screenshots of the web inspector, especially the *requests* tab. Sensitive information such as your account credentials may be on screen and allow someone to compromise your account.
