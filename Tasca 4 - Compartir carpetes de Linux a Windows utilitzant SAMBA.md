Crea un repositori de Github on responguis les següents qüestions: 

Activitat 1

Crea una carpeta a la MV Linux a /srv/samba/compartida1 amb els permisos necessaris perquè pugui accedir tothom.
![image](https://github.com/user-attachments/assets/5666ac40-0975-4ffe-a187-cafbb8268925)

Crea la configuració de SAMBA per compartir la carpeta per a convidats (sense autenticació) amb lectura i escriptura.![image](https://github.com/user-attachments/assets/4c57e693-e5f7-490f-8cc2-2ad418d3bea2)
![image](https://github.com/user-attachments/assets/b4441438-5384-445b-a841-b61e03f550e0)

Reinicia el servei SAMBA.
![image](https://github.com/user-attachments/assets/70632ab9-a717-4cfd-a4fb-d21397183d96)

Comprova que tens accés des de Windows.

Crea algun fitxer a la carpeta.
Comprova que s'ha creat a Linux.
Activitat 2

Crea una carpeta a la MV Linux a /srv/samba/compartida2 amb els permisos necessaris.
Crea un usuari local anomenat user1_X (on X és el teu cognom).
Afegeux l'usuari anterior a SAMBA.
Crea la configuració de SAMBA per compartir la carpeta per a l'usuari anterior amb lectura i escriptura amb màscara de fitxers 755.
Reinicia el servei SAMBA.
Comprova que tens accés des de Windows amb les credencials de l'usuari.
Crea algun fitxer a la carpeta.
Comprova que s'ha creat a Linux i té els permisos 755.
