## Poly dark GRUB theme

Supported languages: Chinese (simplified), English, French, German, Italian, Norwegian, Portuguese, Russian, Spanish, Ukrainian

![](https://i.imgur.com/OHGyR2N.gif)

Screenshot is intentionally low res to fit GitHub UI. See also: [1280×720](https://i.imgur.com/iKtkLr4.png), [1920×1080](https://i.imgur.com/faGEmp5.png)

---

### Installation

With single command line :

`wget https://github.com/Philippe734/poly-dark/archive/master.zip && unzip master.zip && rm master.zip && sudo mkdir -p /boot/grub/themes && sudo mv poly-dark-master /boot/grub/themes/poly-dark && echo "GRUB_THEME=/boot/grub/themes/poly-dark/theme.txt" | sudo tee -a /etc/default/grub && sudo update-grub`

Or step by step :
1. Get theme archive: `wget https://github.com/Philippe734/poly-dark/archive/master.zip`
2. Unpack theme: `unzip master.zip`
3. Remove theme archive: `rm master.zip`
4. Create GRUB themes directory: `sudo mkdir -p /boot/grub/themes`
5. Move theme to GRUB themes directory: `sudo mv poly-dark-master /boot/grub/themes/poly-dark`
6. Set `GRUB_THEME=/boot/grub/themes/poly-dark/theme.txt` in GRUB config: `sudo nano /etc/default/grub`
7. Update GRUB: `sudo update-grub`

---

### See also

- [Poly light GRUB theme](https://github.com/shvchk/poly-light)
- [Fallout GRUB theme](https://github.com/shvchk/fallout-grub-theme)
