# Dyad-Vigo

## Steps to build and start Dyad locally
- git clone [git@github.com:giri-vigo/dyad-vigo.git](git@github.com:giri-vigo/dyad-vigo.git)
- npm install
- sudo chown root:root node_modules/electron/dist/chrome-sandbox
- sudo chmod 4755 -R node_modules/electron/dist/chrome-sandbox
- npx electron-forge start
