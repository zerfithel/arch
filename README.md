Complete installation guide:

> Install git
> - sudo pacman -S git

> Copy the repository
> - git clone https://github.com/zerfithel/arch
> - OR (If you want to use Experimental branch)
> - git clone https://github.com/zerfithel/arch/experimental

> Go to your file localization
> - cd pc
> - cd arch

> Build the package
> - makepkg -si

> Move it to $PATH
> - sudo mv /localization/of/your/pc /usr/local/bin/pc

> Make it executable
> - sudo chmod +x /usr/local/bin/pc

> List the commands:
> - sudo pc -h
