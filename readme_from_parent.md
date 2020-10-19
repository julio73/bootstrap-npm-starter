# Adding starter template as a submodule:
## Usage:
Be sure to have Node.js installed before proceeding.

```
# Clone the repo
git submodule add https://github.com/twbs/bootstrap-npm-starter bootstrap-npm-starter
cd bootstrap-npm-starter

# Install dependencies
npm i

# Compile Sass
npm run css-compile

# Watch Sass for changes (uses nodemon)
npm run watch

# Start local server (uses serve)
npm run server
```

## Add examples:
Download examples from https://getbootstrap.com/docs/4.5/examples/

Then extract the directories in the root forlder `bootstrap-npm-starter`.

Each example can be visited at `/whatever-folder-name` on the localhost server. 