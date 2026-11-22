# Bernie — Linux packages

**Bernie** prepares and runs your laser engraving and cutting jobs: a complete vector editor, photo engraving, color
layers, material tests, preview and estimated time, and control of GRBL, grblHAL, FluidNC, Marlin and Smoothieware
lasers over USB or the network. Free, with no account, no subscription and no ads.
Website: <https://bernie.websolutis.com/>

This repository only hosts the **Linux packages** of Bernie (its source code is not public):

- **Releases**: `.deb` packages (x86_64 and ARM 64-bit, e.g. Raspberry Pi), AppImage and Flatpak bundles.
- **APT repository**: install and updates through `apt` on Debian, Ubuntu, Linux Mint and Raspberry Pi OS:

  ```sh
  curl -fsSL https://beber666.github.io/bernie-releases/bernie.gpg | sudo tee /usr/share/keyrings/bernie.gpg > /dev/null
  echo "deb [signed-by=/usr/share/keyrings/bernie.gpg] https://beber666.github.io/bernie-releases stable main" | sudo tee /etc/apt/sources.list.d/bernie.list
  sudo apt update && sudo apt install bernie
  ```

- **Flatpak repository**: install and updates on any distribution with Flatpak (x86_64 and ARM 64-bit):

  ```sh
  flatpak install --user https://beber666.github.io/bernie-releases/flatpak/bernie.flatpakref
  ```

- **Snap Store**: `sudo snap install bernie` (https://snapcraft.io/bernie).
- **AUR** (Arch Linux, Manjaro): `bernie-bin` (https://aur.archlinux.org/packages/bernie-bin).

USB lasers: your account must be a member of the `dialout` group
(`sudo usermod -aG dialout $USER`, then log out and back in).

---

**Bernie** prépare et pilote vos gravures et découpes au laser. Ce dépôt n'héberge que les **paquets Linux** de Bernie
(le code n'est pas public) : paquets `.deb` (x86_64 et ARM 64 bits, Raspberry Pi), AppImage et Flatpak dans les
« Releases », dépôt APT et dépôt Flatpak (commandes ci-dessus, mises à jour comprises), Snap Store et AUR.
Site : <https://bernie.websolutis.com/fr/>

## Learn more · En savoir plus · Más información · Scopri di più · Mehr erfahren

| | English | Français | Español | Italiano | Deutsch |
|---|---|---|---|---|---|
| Website | [bernie.websolutis.com](https://bernie.websolutis.com/) | [Site](https://bernie.websolutis.com/fr/) | [Sitio](https://bernie.websolutis.com/es/) | [Sito](https://bernie.websolutis.com/it/) | [Website](https://bernie.websolutis.com/de/) |
| Supported lasers | [Compatibility](https://bernie.websolutis.com/compatibility/) | [Compatibilité](https://bernie.websolutis.com/fr/compatibilite/) | [Compatibilidad](https://bernie.websolutis.com/es/compatibilidad/) | [Compatibilità](https://bernie.websolutis.com/it/compatibilita/) | [Kompatibilität](https://bernie.websolutis.com/de/kompatibilitaet/) |
| Features | [Features](https://bernie.websolutis.com/features/) | [Fonctionnalités](https://bernie.websolutis.com/fr/fonctionnalites/) | [Funciones](https://bernie.websolutis.com/es/funciones/) | [Funzionalità](https://bernie.websolutis.com/it/funzionalita/) | [Funktionen](https://bernie.websolutis.com/de/funktionen/) |
| User manual | [Manual](https://bernie.websolutis.com/manual/) | [Manuel](https://bernie.websolutis.com/fr/manuel/) | [Manual de usuario](https://bernie.websolutis.com/es/manual-de-usuario/) | [Manuale](https://bernie.websolutis.com/it/manuale/) | [Handbuch](https://bernie.websolutis.com/de/handbuch/) |
| Downloads | [Download](https://bernie.websolutis.com/download/) | [Télécharger](https://bernie.websolutis.com/fr/telecharger/) | [Descargar](https://bernie.websolutis.com/es/descargar/) | [Scarica](https://bernie.websolutis.com/it/scarica/) | [Herunterladen](https://bernie.websolutis.com/de/herunterladen/) |
| Share a laser | [Bernie Link](https://bernie.websolutis.com/bernie-link/) | [Bernie Link](https://bernie.websolutis.com/fr/partager-laser-bernie-link/) | [Bernie Link](https://bernie.websolutis.com/es/compartir-laser-bernie-link/) | [Bernie Link](https://bernie.websolutis.com/it/condividere-laser-bernie-link/) | — |

© 2026 Websolutis. Bernie is free to download and use; redistribution of these packages is allowed unchanged.
