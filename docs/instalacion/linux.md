# Instalacion en Linux

Esta es la puesta a punto que vas a necesitar para usar la plantilla en tu ordenador con Linux.

## Instalar control de versiones GIT

En tu distribución de Linux lo más normal es que ya venga instalado, pero si no, lo tienes bien explicado en la documentación oficial -> [aquí](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Instalaci%C3%B3n-de-Git#_instalación_en_linux).

Es tan sencillo como abrir una terminal y ejecutar uno de los siguientes comandos.

```bash
# Debian / Ubuntu / Raspbian / Lubuntu / Xubuntu / Linux Mint / Elementary OS / ...
sudo apt install git
# Fedora / Centos / RHEL
sudo yum install git
# Arch / Manjaro / Antergos
pacman -Syu git
```

Luego debes de configurar git en tu sistema con estos dos comandos. Sustituye `<tu-nombre>` por tu nombre y `<tu-email>` por el email que has usado en Github / Gitlab para darte de alta.

```bash
git config --global user.name <tu-nombre>
git config --global user.email <tu-email>
```

## Instalar Python 3

TODO:

## Instalar PIP

TODO:

## Instalar Pipenv

Abre una **terminal**, escribe el siguiente comando y dale a enter.

```bash
pip install pipenv
```

Ya puedes cerrar la terminal.

## Instalar Visual Studio Code

TODO:

## Instalar extensiones de VSCode

TODO:
