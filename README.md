# xvaca

xvaca es un script para xcowsay con nuevos personajes de la vaca de Huayra GNU/Linux.
Muestra un personaje de vaca hacker con frases de adoctrinamiento.

Arte de la vaca de Huayra: Carolina «Chinchi» Hortal, Claudio «Maléfico» Andaur

## Requerimientos

fortune o fortune-mud, xcowsay

## Instalación

* Primeramente instale [https://github.com/ubuntuperonista/Estatuto-del-Hacker]

* Agregue el fichero <file>xvaca</file> en /usr/local/games/ y dele permiso de ejecución. Agrega las gráficas de los personajes en <file>/usr/share/xcowsay</file>. Por ejemplo, en Ubuntu:

<code>cd /tmp ;
git clone https://github.com/ubuntuperonista/xvaca/ ;
sudo cp /tmp/xvaca/xvaca /usr/local/games/;
sudo cp /tmp/xvaca/assets/*.png /usr/share/xcowsay ;
sudo chmod +x /usr/local/games/xvaca</code>

## Uso
Ejecuta el script <file>xvaca</FILE>.

Puedes optar por modificar este script <file>/usr/share/games/xvaca</file> para determinar un tipo de letra y tamaño diferente, o cambiar los personajes:

<file>/usr/share/xcowsay/est_vaca.png</file>

<file>/usr/share/xcowsay/vaca.png</file>

<file>/usr/share/xcowsay/vaca_hacker.png</file>

<file>/usr/share/xcowsay/vaca_volando.png</file> 

<file>/usr/share/xcowsay/ubuntu_peronista.png</file>

<file>/usr/share/xcowsay/vaca_volando.png</file>

<file>/usr/share/xcowsay/super_vaca.png</file>

<file>/usr/share/xcowsay/tux_kirchnerista_ubuntero.png</file>
