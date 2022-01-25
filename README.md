Qawl v2

**Current status**: 80% parity with previous version (missing dark theme, icons on hover tooltips, mostly)

This project uses Github Projects to plan development — feel free to [join in](https://github.com/sufone/qawl/projects)!

Feel free to email me if you are interested in contributing right now, before the foundation is done: navedcoded@gmail.com . Sorry if things are a bit messy, but I recommend checking this repo out a few weeks later!


Old version: https://github.com/mr-islam/qawl

Sorry this readme is bad, making it public quickly in case people want to contribute early ♥

# Development
Preparation
1. Make sure you have `node` properly setup with a recent version (I use 14.x).
2. Install `yarn`
3. Also ensure you have node-gyp ([this guide can help](https://github.com/nodejs/node-gyp))
4. Clone this repo
5. Run `yarn` to install dependencies

(The repo uses an automatic `postinstall` script to patch the npm package `electron-update-notification` to use a promise `.then()` instead of callbacks. I haven't been able to test if I set this up correctly, but hopefully it's fine. You can check the installed package files manually, or just message me for help to ensure it's all good.)

Action
5. Run a local build with `electron-dev`, has hot-reload
6. Build a package with `dist-[platform]` choosing the relevant platform from the scripts available in the `package.json`


*Many thanks to Albert Nye for his svelte electron template!*


# License

    Copyright (C) 2020-2021 Naved Islam

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published
    by the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
