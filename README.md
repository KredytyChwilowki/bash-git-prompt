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

Uwaga! Aby symbole poprawnie Wam się wyświetlały w konsoli, trzeba ustawić sobie czcionkę "DejaVu Sans Mono" (środkowoeuropejski).
Można to zrobić w Putty:
1) klikając na tytule okna prawym przyciskiem myszki
2) z menu wybrać "Change Settings..."
3) w oknie ustawień - z menu po lewej stronie wybrać "Window" / "Apperance" 
4) po prawiej stronie w sekcji "Font settings" kliknąć w "Change..." i wybrać odpowiednią czcionkę.

Pewnie jakieś inne czcionki też dobrze działają, pamiętajcie tylko aby to była czcionka o stałej szerokości znaków.
Jak zamiast symboli macie jakieś krzaczki/kwadraciki to znaczy, że macie ustawioną złą czcionkę.