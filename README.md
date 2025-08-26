# 🚀 Bot Setup Instructions

Welcome to the bot setup guide! Follow the steps below to install and configure the bot correctly.  
[Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux)

---

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Installation Steps](#installation-steps)
3. [Configuration Files](#configuration-files)
4. [Running the Bot](#running-the-bot)
5. [Contact and Support](#contact-and-support)

---

<details>
<summary><h2>1. Prerequisites</h2></summary>

Before running the bot, make sure you have the following installed:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).

👉 Double click `run.bat` for Windows or `run.sh` for Linux/Mac to run automatically (remember to fill configs).

</details>

---

<details>
<summary><h2>2. Installation Steps</h2></summary>

1. **Download and Extract the Bot Files**
   - Extract the bot package into a folder on your computer.

2. **Install Dependencies**
   ```bash
   npm install --force user-agents axios colors https-proxy-agent socks-proxy-agent tweetnacl crypto-js ws uuid @solana/web3.js bs58
 ```

If Execution Policy error on Windows:

```bash
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

3. **Prepare Config Files**

   * Make sure all files are ready before running.

</details>

---

<details>
<summary><h2>3. Configuration Files</h2></summary>

### `configs.json` - 📜 Adjust Bot Settings

```json
{
  "rotateProxy": false,
  "skipInvalidProxy": false,
  "proxyRotationInterval": 2,
  "delayEachAccount": [1, 1],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 100,
  "referral": true,
  "referralCodes": ["bGAxXum"]
}
```

### `privateKeys.txt` - 🗂️ Wallets

```txt
privatekey
privatekey
privatekey
```

### `proxies.txt` - 🌐 Proxies (Optional)

```txt
http://host:port
https://user:password@host:port
socks5://host:port
```

</details>

---

<details>
<summary><h2>4. Running the Bot</h2></summary>

```bash
cd /path/to/meomundep-folder
node meomundep.js
```

</details>

---

<details>
<summary><h2>5. Contact and Support</h2></summary>

* **Referral Link**: [Play Solarena](https://play.solarena.io/) | Code: `bGAxXum`
* **Buy me a telegram account** [Here](https://t.me/KeoAirDropFreeNe/312/27801)

**Support:**

* [Contact Me](https://t.me/MeoMunDep)
* [Join Group](https://t.me/KeoAirDropFreeNe)
* [Channel](https://t.me/KeoAirDropFreeNee)

</details>

---

Enjoy using the bot! 🚀

