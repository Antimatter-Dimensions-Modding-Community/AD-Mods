# Antimatter Dimensions

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/652694d14b7a41d582f466d09f62c435)](https://app.codacy.com/gh/Antimatter-Dimensions-Modding-Community/AD-Mods?utm_source=github.com&utm_medium=referral&utm_content=Antimatter-Dimensions-Modding-Community/AD-Mods&utm_campaign=Badge_Grade)

## Run

To run the game locally, you will need to install
[Node.js](https://nodejs.org/) (LTS suggested).

First, run the following command in your terminal (or command line) while being
inside the checked out repository:

```
npm ci
```

After all the packages are installed, start up the game:

```
npm run serve
```

This will make the game served via your localhost, and the playable link will
be displayed in your terminal. The server **doesn't** need to be restarted
after you've made changes - just reload the page. The server **can**
occasionally crash, so check your terminal from time to time and run `serve`
again if needed.
