# Hyprland
Esta es quizá la forma más sencilla de configurar su sistema ArchLinux para una experiencia minimalista con HyprLand.

<br>

<b> Requisitos: </b>
</br>
Instalación mínima y limpia de Arch con HyprLand </br>
Prefiero el Display Manager Ly
<br>

<b> Instalamos Git</b>
</br>
```
sudo pacman -S git
```
<br>

<b> Instalamos PARU </b>
</br>
Clonamos el repositorio, ingresamos a la carpeta correspondiente y compilamos con la siguiente línea
```
git clone https://aur.archlinux.org/paru-bin.git && cd paru-bin && makepkg -Si
```
<br>

<b>Instalamos las dependencies y paquetes necesarios </b>
</br>
```
paru -S imv wlogout brightnessctl wl-clipboard waybar-hyprland swaylock-effects wofi pavucontrol pamixer file-roller htop ttf-font-awesome ttf-jetbrains-mono-nerd noto-fonts-emoji hyprpaper linux-headers alsa-utils less wlroots gnu-free-fonts noto-fonts ttf-bitstream-vera ttf-croscore ttf-dejavu ttf-droid ttf-ibm-plex ttf-liberation udiskie grim slurp
```
<br>

<b> Tomando precauciones </b>
</br>
Copiamos el archivo de configuración original en la raíz del usuario para tenerlo respaldado
```
cp ~/.config/hypr/hyprland.conf ~/
```
<br>

<b> Instalando el tema </b>
</br>
Clonamos este repositorio y copiamos la configuración a nuestra carpeta
```
https://github.com/andriuzha/HyprLand.git && cd hyprland && cp -R *.conf ~/.config/hypr/
```
<br>

<b> Configurando el Wallapaper </b>
</br>
Dentro de la carpeta *~/.config/hypr/* esta el archivo *hyprpaper.conf*  que indica la ruta de la imagen. </br>
Por defecto es: ~/wallpaper/wallpaper.jpg Puede configurarlo a su preferencia.
<br>



<b> Screenshots </b>
</br>
Aquí hay unas capturas de pantalla del entorno una vez finalizada la configuración
<br>

<img align="center" src="/screenshot1.png">
*Wallpaper tomado de https://wallpaperset.com/*
<br>

<img align="center" src="/screenshot2.png">
