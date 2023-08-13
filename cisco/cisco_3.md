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
