# Managing your instance

You will need to create a guild to manage your Makita instance. I trust you know how to make
a guild. Once you've made your management guild, you'll need to invite your bot. This must
be done before the first launch of the bot.

### Getting an invite link

You can run `./makita invite -i <bot id>` to generate an invite link for the bot. Once you
have the bot running, you can also use the `/info` command to get an invite link.

### Updates

You can check for updates with the `/makita checkupdates` command and apply updates with the
`/makita update` command. It will automatically restart, but you can restart manually with
`/makita restart`. The bot also handles keyboard interrupts and cleanly shuts down in
response to them, so feel free to be a bit rough with it.