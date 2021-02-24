# Práctica 2

### Renato Josué Flores Pérez 	   - 201709244
### Ronald Gabriel Romero González - 201701048
### Eddie Augusto Salazar	   - 201700326

## Topología de red
![image](images/topologia.png)

## VTP

- *dominio*: Grupo16
- *password*: Grupo16

### Vlans creadas

- **Administración** - Vlan 16
- **Profesores** - Vlan 26
- **Clase A** - Vlan 36
- **Clase B** - Vlan 46

## Direcciones de Red

| Vlan | Direccion de Red | Primera Direccion Asignable | Ultima Direccion Asignable | Direccion de Broadcast | Gateway | Máscara de subred |
|:----------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-----------------------:|:----------------------------:|
| 16 | 192.168.56.0 | 192.168.56.1 | 192.168.56.62 | 192.168.56.63 | 192.168.56.1 | 255.255.255.192 |
| 26 | 192.168.56.64 | 192.168.56.65 | 192.168.56.126 | 192.168.56.127 | 192.168.56.65 | 255.255.255.192 |
| 36 | 192.168.20.128 | 192.168.56.129 | 192.168.56.190 | 192.168.56.191 |192.168.56.129 | 255.255.255.192 |
| 46 | 192.168.10.192 | 192.168.56.193 | 192.168.10.254 | 192.168.56.255 |192.168.56.193 | 255.255.255.192 |

## Spanning Tree Protocols

### STP
### RSTP
### PVSTP

## Port Channels
