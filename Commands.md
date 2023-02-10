### Supervisar la ejecución de un comando
```
watch -n1 -b "<comando-a-supervisar>"
```
###Ejecución de dos o más comandos en terminal
```
git pull; git pull
git pull && git pull
git pull || git pull
```
https://es.phhsnews.com/how-to-run-two-or-more-terminal-commands-at-once-in-linux2378

### Ejecucion de un archivo .bat
```
start <nombre-archivo>.bat
```

> ls | grep <palabra-clave> | xargs -I{} git -C {} pull

Realiza un *git pull* en los repositorios que contengan la palabra clave.

> sudo apt install gnome-tweaks

Habilita el uso de los botones el mouse en Ubuntu 22.04 (máquina virtual).