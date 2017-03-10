# Notes for Developers

## Developing

    $ npm install
    $ npm start

## Building a Release

If cross-compiling from Mac to Windows, install [Wine](see https://github.com/electron-userland/electron-builder/wiki/Multi-Platform-Build) first.

    $ npm run build:mac # Mac only
    $ npm run build:win # Windows only
    $ npm run build     # Mac and Windows