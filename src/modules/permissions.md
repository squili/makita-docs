# Permissions

The bot has a few permissions that determine who can access certain commands and do certain
things. Each permission entry has a set of Discord permissions that can use it (for example,
by default, people with the `Manage Server` Discord permission has the `Manage Previews`
Makita permission) and a set of roles and users who have it. All of this can be configured
with the `/permissions` command. Note that, because of limitations in Discord, you'll need
to [calculate the permissions bits yourself](https://discordapi.com/permissions.html).

Name               | Description                  | Default      
-------------------|------------------------------|--------------
Administrator      | Access to all permissions    | Administrator
Manage Permissions | Manage bot permissions       | Administrator
Manage Previews    | Manage preview configuration | Manage Server
