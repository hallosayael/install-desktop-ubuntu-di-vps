# INSTAL DESKTOP UBUNTU DI VPS (GUI)
# Instal On CLI
## Update
```
sudo apt update
```
## 1. Install curl
```
sudo apt install curl
```
## 2. Buat username dan password untuk masuk ke desktop nanti
```
curl -O https://gist.githubusercontent.com/NodeFarmer/a533a2e5e7ae8174e06d8e8830721ab6/raw/UbuntuDesktop.sh && chmod +x UbuntuDesktop.sh && ./UbuntuDesktop.sh
```
## 3. DONE
## 4. Buka aplikasi untuk remote desktop
## 5. Input IP VPS
## 6. Masukan username dan password yang dibuat tadi
## Selamat kamu sudah masuk di vps dengan tampilan desktop
# UNINSTALL DESKTOP
```
sudo apt purge --auto-remove xfce4 xfce4-* lightdm ubuntu-desktop gnome-shell xrdp -y && sudo apt autoremove -y && sudo apt autoclean -y
```

