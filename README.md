IDENA BLOCKCHAIN SNAPSHOT
============
[![Frequency Daily](https://img.shields.io/badge/frequency-daily-green)](https://github.com/ltraveler/idenachain.db/commits/main) [![Last Commit](https://img.shields.io/github/last-commit/ltraveler/idenachain.db/main)](https://github.com/ltraveler/idenachain.db/commits/main) [![IDENA Blockchain Repository Size](https://img.shields.io/github/repo-size/ltraveler/idenachain.db)](https://github.com/ltraveler/idenachain.db/)

The snapshot will help you to sync your Idena Node in a matter of minutes.

![IDENA Blockchain Fast Synchronization](https://github.com/ltraveler/ltraveler/raw/main/images/idenachain.db_deployment.gif)

---
## ☕ Buy me a coffee

Whether you use this project, have learned something from it, or just like it, please consider supporting it by buying me a coffee, so I can dedicate more time on open-source projects like this :)

- **💳 Address for donations:**
`0xf041640788910fc89a211cd5bcbf518f4f14d831`

- **🔗 URL to autosend (100 iDNA) via Idena web-client or Idena client app:**
`dna://send/v1?address=0xf041640788910fc89a211cd5bcbf518f4f14d831&amount=100&comment=Buy%20Me%20A%20Coffee&callback_url=https%3A%2F%2Fgithub.com%2Fltraveler%2Fidenachain.db`

---

## ⚓ Default path to idenachain.db

Depends on your OS the path to 'idenachain.db' directory would be different.
This table helps you to choose the correct path based on your operational system.

- `Linux/macOS/Windows`
  - The default path value to idenachain.db varies across OSes:
    | OS          | Path                                     | Example                                    |
    | ----------- | ---------------------------------------- | ------------------------------------------ |
    | Linux / Ubuntu | `~/idena-go/datadir/` | `/home/Olga/idena-go/datadir`                 |
    | macOS       | `cd ~/Library/Application\ Support/Idena/node/datadir`      | `cd ~/Library/Application\ Support/Idena/node/datadir` |
    | Windows     | `%AppData%\Idena\node\datadir`           | `C:\Users\Olga\AppData\Roaming\Idena\node\datadir`           |

---

## 🐧 💡 How to make fast sync in Linux (Ubuntu)
1. `sudo service idena_username stop` — stop current idena-go instance;
2. `cd ~/idena-go/datadir/` — switch your current directory to _**datadir**_;
3. `rm -rf idenachain.db` — remove current **_idenachain.db_** folder;
4. `git clone -b main --depth 1 --single-branch https://github.com/ltraveler/idenachain.db.git` — clone the snapshot of idenachain.db folder (official git package must be installed `sudo apt-get update && sudo apt-get install git-all`);
5. `rm -rf ./idenachain.db/.git` — remove unnecessary **_.git_** folder;
6. `sudo service idena_username stop` — start current idena-go instance.

#### ⏰ Updated once a day

---

## 🪟 💡 Idena fast synchronization in Windows (Power Shell)
1. `Get-Process -Name 'Idena','Idena-go' | Stop-Process -Force` — stop idena-go network node and idena desktop client;
2. `cd $env:APPDATA\Idena\node\datadir` — switch your current directory to _**datadir**_;
3. `Remove-Item -Recurse -Force idenachain.db` — remove current **_idenachain.db_** folder;
4. `git clone -b main --depth 1 --single-branch https://github.com/ltraveler/idenachain.db.git` — clone the snapshot of idenachain.db folder (official git windows client is available here https://git-scm.com/download/win);
5. `Remove-Item -Recurse -Force ./idenachain.db/.git` — remove unnecessary **_.git_** folder;
6. Start idena desktop client and idena-go network node.

#### ⏰ Updated once a day

---

## 🍏 💡 How to use idena blockchain snapshot in macOS
1. `killall -m idena` — stop idena-go network node and idena desktop client;
2. `cd ~/Library/Application\ Support/Idena/node/datadir` — switch your current directory to _**datadir**_;
3. `rm -rf idenachain.db` — remove current **_idenachain.db_** folder;
4. `git clone -b main --depth 1 --single-branch https://github.com/ltraveler/idenachain.db.git` — clone the snapshot of idenachain.db folder (official git MacOS client is available here https://git-scm.com/download/mac);
5. `rm -rf ./idenachain.db/.git` — remove unnecessary **_.git_** folder;
6. Start idena desktop client and idena-go network node.

#### ⏰ Updated once a day

---

## ℹ️ Other information
* If you are looking for a stable shared node service, please contact me on **Telegram**  `@ltrvlr`

---

## 💬 Contact information
* **📧 Email** `ltraveler@protonmail.com`
* **🗨️ Telegram** `@ltrvlr`
