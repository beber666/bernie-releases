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

- **Snap Store** and **AUR** (coming soon).

USB lasers: your account must be a member of the `dialout` group
(`sudo usermod -aG dialout $USER`, then log out and back in).

---

**Bernie** prépare et pilote vos gravures et découpes au laser. Ce dépôt n'héberge que les **paquets Linux** de Bernie
(le code n'est pas public) : paquets `.deb` (x86_64 et ARM 64 bits, Raspberry Pi), AppImage et Flatpak dans les
« Releases », dépôt APT et dépôt Flatpak (commandes ci-dessus, mises à jour comprises), bientôt le Snap Store et l'AUR.
Site : <https://bernie.websolutis.com/fr/>

© 2026 Websolutis. Bernie is free to download and use; redistribution of these packages is allowed unchanged.
