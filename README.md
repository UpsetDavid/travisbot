# travisbot

It's a Twitch bot.

## Running

Set up a file named `config.js` in the root directory. It should export a config object as the default export.
An example config file, showing the correct structure with sensitive information removed, can be found at [config.example.js](./config.example.js).

See [this link](https://dev.twitch.tv/docs/irc/) for descriptions of the variables in the `tmiOptions` object.
The structure of `tmiOptions` should match the config object in the example.

See [this link](https://dev.twitch.tv/docs/api/) for information about the `apiClientId` field,
as well as how to acquire one of these keys.
This is used to make requests to the Twitch API for things like stream uptime.

Run the bot using `node index.js`, or by running `npm start` in the repository's root directory.
