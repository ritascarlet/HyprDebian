# HyprDebian
Simple setup script for installation Hyprland On Debian(sid)

I love you very much Debian and works Vaxerski, so I decided to write a simple script (really very simple), which collects all the components from the source code. 
(wayland, wayland-protocols, libdisplay-info, hyprlang, hyprcursor, hyprwayland-scanner, aquamarine) and (sddm without kde, kitty, wofi and hyprpaper)


The script always collects the latest versions of dependencies and the most Hyprland, which in theory could cause failures during a global update of any of the components.

It is recommended to set it to CLEAN debian sid And yes, debian sid more stable, more comfortable and safer than the same testing

Okay, I wrote a lot. Let's get started with the installation.

wget https://github.com/ritascarlet/HyprDebian/blob/main/HyprDebian.sh

chmod +x HyprDebian.sh

sudo ./HyprDebian.sh

By the way, run only from root

If you want to contribute your idea for the script, then say so, don't be shy. Love and hugs to all<3
