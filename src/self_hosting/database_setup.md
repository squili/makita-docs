# Setting up the database

1. [Install Postgres](https://www.postgresql.org/download/)
2. Connect to the database with the `psql` tool
   1. You may need to use `sudo su postgres -c psql` to run the command from the right user
3. Create a user for the bot
   1. The command you're looking for is `create user <user_name> with password '<password>'`
4. Create a database for the bot
   1. The command for this is `create database <database_name> with owner <user_name>`
5. Construct your database url
   1. The format is `postgres://<user_name>:<password>@localhost/<database_name>`

You'll be using your database url in a future step to configure the bot