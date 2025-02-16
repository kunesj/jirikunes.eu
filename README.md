# jirikunes.eu

Source of the jirikunes.eu web page.


## Website Setup

### Install Node.js

```bash
nvm install 16.20
nvm use 16.20
```

If you are running this with Pycharm, the NVM ENV variables must be copied from `~/.bashrc` to `~/.profile`. These ones:

```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
```

### Build assets

```bash
cd website
npm install
npm run build
```

### Run local server

```bash
cd website
npm run preview
```


## Development

Use pre-commit
```bash
pre-commit install
```
