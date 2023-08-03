# Yolks

A curated collection of core images that can be used with Pterodactyl's Egg system. Each image is rebuilt
periodically to ensure dependencies are always up-to-date.

Images are hosted on `ghcr.io` and exist under the `games` spaces. The following logic
is used when determining which space an image will live under:

* `games` — anything within the `games` folder in the repository. These are images built for running a specific game
or type of game.

## Available Images

* [`games`](https://github.com/magnalunar/yolks/tree/master/games)
  * [`source`](https://github.com/magnalunar/yolks/tree/master/games/source)
    * `ghcr.io/magnalunar/games:source`
