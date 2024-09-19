Welcome!
To make this script work first read how this work and if you dont know how to, use AI to translate it so you know how it works.
Then do
sudo chmod +x pc
This will give "pc" script executing permissions
Then do
mv /localization/of/pc.script/ /usr/local/bin
This will allow script to be executed even if your not at script directory
To remove this package after adding it do /usr/local/bin simply do:
sudo rm -rf /usr/local/bin/pc (or script name)

Author: Zerfithel
Discord (HELP CENTER): https://discord.gg/dfbpeQChHM

Commands:
sudo pc install [package_name]
Does: sudo pacman -S [package name]
sudo pc remove [package name]
Does: sudo pacman -Rnsn [package name]
sudo pc update
Does: sudo pacman -Syy
sudo pc upgrade
Does: sudo pacman -Syyu
