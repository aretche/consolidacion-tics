# Instalar LXC en Ubuntu / Debian de 64 bits

## Instalar los paquetes necesarios

Instalar los paquetes de LXC

```
sudo apt-get install lxc lxc-templates debootstrap lxctl
```

Instalar los paquetes para la configuración avanzada

```
sudo apt-get install cgroup-lite redir bridge-utils
```

Instalar el soporte para LXC en vagarant:

```
sudo apt-get install vagrant-lxc
```

Instalar el plugin vagrant para el usuario actual

```
vagrant plugin install vagrant-lxc
```

Reiniciar el equipo y volver a ingresar.


## Verificar que capacidades soporta/tiene activadas el sistema

```
lxc-checkconfig
```

