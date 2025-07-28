# Vencore

**Vencore** is a secure and enhanced fork of [Vencord](https://github.com/Vendicated/Vencord), introducing new plugins, additional custom features, including experimental patches, better mobile and web support and more.

✅ No telemetry  
✅ No forced installer  
✅ Weekly builds from a trusted source  
✅ Compatible with latest Discord versions  
✅ Runs safely and cleanly inside the Discord app folder

---

## ✨ Features

- Over 200+ plugins
- Removed/legacy plugins restored
- Manual/Automatic installation with easy ZIP deployment
- No background services or startup bloat
- Weekly updates via `.zip` from a controlled CDN

---

## Installation

> Vencore works without the official installer and doesn't modify the system — only the Discord app folder however it cannot work without previously installing Vencord (for now!).

### 1. Locate Vencord’s `dist` folder

Usually found in:
For Windows:

```
%APPDATA%\Vencord/dist
```
For Linux: 
```
~/.config/Vencord/dist
```

Make sure Discord is **closed**.

---

### 2. Backup the original `dist` folder

Rename `dist` → `dist.orig` (optional but recommended if you'd like to fastly switch back to Vencord)

---

### 3. Download and extract the latest Vencore build

Latest build:  
[Download ZIP](https://example.com)

Extract the contents of the `.zip` into the `Vencord/dist` folder.

---

## Updating

Vencore is updated **weekly**. Just:

1. Close Discord  
2. Download the newest ZIP from the CDN  
3. Overwrite the `dist` folder with new contents

> You may automate this with the Vencore Installer Update feature (soon).

---

## Is it safe?

Yes!

- Vencore is based on the open-source Vencord framework
- Builds are published manually and transparently
- No telemetry or network requests added
- Only runs within the Discord app process
- All plugin code is readable and modifiable

You can inspect any build or source [here](https://github.com/vencore-official/vencore).

---

## Development / Building

To build Vencore from source:

```bash
git clone https://github.com/ApexTeamPL/Vencore-Dev
cd Vencore-Dev
pnpm install
pnpm build # use pnpm buildWeb for web
```

After building, you can zip the `dist/` folder and use it as your update package.

---

## Credits

- Original project: [Vencord](https://github.com/Vendicated/Vencord)
- Mods, rebuilds & CDN by **ApexTeam**
- Contributors: see GitHub commit log
- Join our Discord [here](https://discord.gg/qKrmbcUErC)

---

## License

Vencore is licensed under the **GPLv3**, same as Vencord.

> "This program is distributed in the hope that it will be useful,  
but WITHOUT ANY WARRANTY..."

---
