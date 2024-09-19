# mongodb
mongodb installation packages for ubuntu
https://www.mongodb.com/try/download/database-tools
## mongoDB installation:
  1. clone the repo
  ```
  git clone https://github.com/fdmxfarhan/mongodb.git
  ```
  2. go inside the folder
  ```
  cd "mongodb/Ubuntu 22.04 x64"
  ```
  3. install the package
  ```
  sudo dpkg -i mongodb-org-server_8.0.0_amd64.deb
  ```
  4. try this to install any dependency needed.
  ```
  sudo apt --fix-broken install
  ```
## Node and NPM installation:
  1. update package list
  ```
  sudo apt update
  ```
  2. Install Prerequisites
  ```
  sudo apt install -y curl gnupg
  ```
  3. Add NodeSource Repository
  ```
  curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
  ```
  4. Install Node.js and npm
  ```
  sudo apt install -y nodejs
  ```
  5. Upgrade npm to v8.19.3
  ```
  sudo npm install -g npm@8.19.3
  ```
## done!!
