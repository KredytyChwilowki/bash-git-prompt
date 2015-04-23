# Kolorowanie w bashu + pełne wsparcie dla gita z autouzupełnianiem :)

Jest to FORK z https://github.com/magicmonty/bash-git-prompt dostosowany do mojego skryptu koloryzujacego basha.
Instalacja:

```sh
sudo install -m 777 -d /dane/skrypty/
cd /dane/skrypty/ 
sudo git clone git@192.168.10.100:m.rygiel/bash-git-prompt.git
sudo cp -f /dane/skrypty/bash-git-prompt/etc/bashrc /etc/bashrc
```

Po czym trzeba sie przelogowac.
Efekt koncowy:

![Example prompt](git-bash-rm-screenshot.png)
