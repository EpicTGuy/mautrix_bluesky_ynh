## Log in to Bluesky

In your Matrix client, start a direct chat with `@__BOTNAME__:__SERVER_NAME__` (if it isn't found in the user directory, type the full ID). Use an **encrypted** chat if possible, since you will send credentials in it.

Send `login` to the bot, then your server (`bsky.social` by default), your handle or email and your password. An app password works if it has access to direct messages.

Once logged in, your conversations appear as Matrix rooms. Useful commands: `help`, `list-logins`, `logout <login ID>`. Logs: `sudo yunohost service log __APP__`.
