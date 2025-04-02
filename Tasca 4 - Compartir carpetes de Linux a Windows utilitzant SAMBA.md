Crea un repositori de Github on responguis les següents qüestions: 

Activitat 1

Crea una carpeta a la MV Linux a /srv/samba/compartida1 amb els permisos necessaris perquè pugui accedir tothom.
![image](https://github.com/user-attachments/assets/5666ac40-0975-4ffe-a187-cafbb8268925)

Crea la configuració de SAMBA per compartir la carpeta per a convidats (sense autenticació) amb lectura i escriptura.![image](https://github.com/user-attachments/assets/4c57e693-e5f7-490f-8cc2-2ad418d3bea2)
![image](https://github.com/user-attachments/assets/b4441438-5384-445b-a841-b61e03f550e0)

Reinicia el servei SAMBA.
![image](https://github.com/user-attachments/assets/70632ab9-a717-4cfd-a4fb-d21397183d96)

Comprova que tens accés des de Windows.
![image](https://github.com/user-attachments/assets/3a782d19-8869-4db0-8599-88c8ed66d2e5)

Crea algun fitxer a la carpeta.
![image](https://github.com/user-attachments/assets/6b397719-8903-42d7-bf3a-63c8da306d9f)

Comprova que s'ha creat a Linux.
![image](https://github.com/user-attachments/assets/0564ba91-c147-44a5-9272-32aed84c4608)

Activitat 2

Crea una carpeta a la MV Linux a /srv/samba/compartida2 amb els permisos necessaris.
![image](https://github.com/user-attachments/assets/507f32ef-9457-4ee2-9243-cf560a8fe99d)

Crea un usuari local anomenat user1_X (on X és el teu cognom).
![image](https://github.com/user-attachments/assets/f7865fdd-20bb-445e-8bd9-65180a4312b0)

Afegeux l'usuari anterior a SAMBA.
![image](https://github.com/user-attachments/assets/75b6bf9b-e819-4a93-ac3f-b9b8476a8847)

Crea la configuració de SAMBA per compartir la carpeta per a l'usuari anterior amb lectura i escriptura amb màscara de fitxers 755. ![image](https://github.com/user-attachments/assets/cdecb87d-5e6c-49b4-b0cd-d6baa47e2bc0)

Reinicia el servei SAMBA.
![image](https://github.com/user-attachments/assets/dabaf42c-2fb4-49d0-b9f4-c7f16248a201)

Comprova que tens accés des de Windows amb les credencials de l'usuari.
![427494373-8df30648-7b8e-4486-84cf-9e930f258979](https://github.com/user-attachments/assets/91dfaded-2347-4ac4-a7d7-ec7a3eac90ce)

Crea algun fitxer a la carpeta.
![image](https://github.com/user-attachments/assets/d8a9d8d3-9906-426d-805c-f688a4fd3d25)

Comprova que s'ha creat a Linux i té els permisos 755.
![image](https://github.com/user-attachments/assets/d6849a7e-7e7e-4ae4-a294-b7a6a77d3180)
