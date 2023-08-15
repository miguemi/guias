# VTP

```bash
# ver el modo de vtp del switch
show vtp status
vtp mode [client, password, transparent]
# establecer el dominio
vtp domain cisco
# establecer la contra
vtp password 2023
```

# Etherchannel
```bash
# seleccionar los puertos de un solo
int range g0/1-2

# crear el gupo
channel-group 1 mode active

# modificar la interfaz
int port-channel 1

# show relevante
show etherchannel 
show etherchannel port-channel
show etherchannel summary``

# Eliminar
eliminar el canal
# de cisco
```

# ACL
```bash
# ACL estandar

# bloqueo especifico
acces-list 1 deny host 192.168.100.2
# acceso general
acces-list 1 any

int g0/0
ip access-group 1 out
```
