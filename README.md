![Example](/assets/ignore/banner.png)

> A Growtopia private server using Node.js

## Requirements

- Node.js v16+ (Recommended LTS v20)

## Setup

To setup the server, first install necessary packages & settings by

```
$ npm install
```

And congrats setup are done, simple as that!
Now you just need to run the server by

```
$ npm run dev
```

## Enviroment file

Example for default .env file (Generated automatically)

```
ENCRYPT_SECRET=SUPERSECRET # Default encrypt secret
WEB_ADDRESS=127.0.0.1
WEB_ENV=development
```

## Database

Database that we currently use is SQLite, since its easier & light instead of using JSON.
And for the ORM we are using [Drizzle-ORM](https://orm.drizzle.team/)

## Starting server

To run the development server by

```
$ npm run start
```

## Development

For the hosts file you can see this example below

```
127.0.0.1 www.growtopia1.com
127.0.0.1 www.growtopia2.com
127.0.0.1 login.growserver.app # New login system for development purposes
```

## Growtopia assets cache

Where the heck is `assets/cache.zip` come from? Its basically a growtopia assets file cache that required by items.dat to load the game.

![Example](/assets/ignore/updating_items.png)

Location:

- Windows: `%LOCALAPPDATA%/Growtopia`

Then zip the `cache` folder into zip & put it to `assets/cache.zip`.

### Issue

If you encountered `Updating items...` then disconnected from the server randomly. Update the cache by login to Growtopia's original server & do [this](#growtopia-assets-cache) step again.

## Contributing

Any contributions are welcome.

There's few rules of contributing:

- Code must match the existing code style. Please make sure to run `npm run lint` before submiting a PR.
- The commit must take review first before merging into `main` branch.

## Links

- [Discord Server](https://discord.gg/sGrxfKZY5t)

## Credits

Give a thumbs to these cool people:

- [Alexander (Syn9673)](https://github.com/Syn9673)
- [Restart](https://github.com/iRestartz)
- [Ritshu](https://github.com/Ritshu)
