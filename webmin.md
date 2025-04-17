1.- Crear i modificar usuaris
Has de crear dos usuaris bakalao_X i techno_X on (X és el vostre cognom).
![image](https://github.com/user-attachments/assets/e2dd09a7-2cf0-4a12-94b8-2c5aebd5db6b)
![image](https://github.com/user-attachments/assets/cace2270-6c68-4d83-8553-448e1653a32b)

Els usuaris et passaran el hash de la seva contrasenya, no la contrasenya real. (podeu fer servir openssl).
![image](https://github.com/user-attachments/assets/b17b4beb-f9c0-42f5-90aa-ab934a94c9aa)

Cada usuari tindrà un directori a home igual al seu nom d'usuari.
![image](https://github.com/user-attachments/assets/0ddf1cdc-c302-4c0d-8988-559741d26cd9)
![image](https://github.com/user-attachments/assets/585fdf5f-dad4-4cf2-b4fc-ab0065d4ca0a)

Utilitzaran bash com a shell.
![image](https://github.com/user-attachments/assets/be4198da-437e-4aac-9a92-2f26647570a7)

Els usuaris estaran dins del grup que tingui el seu mateix nom i dins del grup usuaris_empresa.
![image](https://github.com/user-attachments/assets/112213d0-5cc1-4661-8e1f-8f6e48ff5df3)

L'usuari techno no podrà fer login després del dia 31-03-2025.
![image](https://github.com/user-attachments/assets/484dc215-fa83-47dc-8bf5-f591eff97e1a)

Comproveu que els usuaris poden iniciar sessió.
![image](https://github.com/user-attachments/assets/215fe26a-da05-4632-a901-bac0b2550cba)

2.- Programar tasques
Programa una tasca que neteja els paquets de Linux que ja no s'utilitzen una vegada al mes.
![image](https://github.com/user-attachments/assets/9f437b3e-f2ed-4fed-88ae-587d3a74d102)

Programa una tasca diaria que apaga l'ordinador a les 14:00.
![image](https://github.com/user-attachments/assets/b9415eae-f203-4405-8a38-0ba5c131d665)

Comprova que funcionen (canvia dia i hora del sistema mitjançant webmin).
![image](https://github.com/user-attachments/assets/764279ca-04cd-4d52-bced-fcdcee09563f)
![image](https://github.com/user-attachments/assets/2f2cde95-f5b1-4098-ad20-e3b83fc2c122)

3.- Instal·lació de software
Utilitza webmin per mostrar quins paquets de software es podrien actualitzar.
![image](https://github.com/user-attachments/assets/edd0a981-cbc1-4ec1-bd5c-bafa03ba2cc6)

Des de webmin actualitza un paquet.
![image](https://github.com/user-attachments/assets/18d2f773-5dc4-4fa8-80b5-4e33b39fc425)

Utilitza webmin per instal·lar un joc de apt.
![image](https://github.com/user-attachments/assets/e798e532-f71f-4ee0-9742-2967f7bdb232)

Utilitza webmin per instal·lar gimp de apt.
![image](https://github.com/user-attachments/assets/081d7292-78eb-4187-a322-9da71e0e50e2)
![image](https://github.com/user-attachments/assets/7f210ceb-6e91-4389-acb6-2c4bf67cea7e)
![image](https://github.com/user-attachments/assets/a2333961-b90f-4e22-bd77-1b5a77018d64)

Utilitza webmin per desinatl·lar el joc que heu instal·lat abans.
![image](https://github.com/user-attachments/assets/b0d9f785-b09f-41e9-bd92-9e310c6d4028)

4.- Serveis
Utilitza webmin per mostrar els serveis que s'inicien amb el sistema.
![image](https://github.com/user-attachments/assets/df59bc42-35a9-4370-9051-d42723ff30cf)

Utilitza webmin per mostrar els serveis que estan actius.
![image](https://github.com/user-attachments/assets/2bb1217a-8be7-4d0c-a2c0-67d09ee2ce3c)

Utilitza webmin per mostrar l'estat del servidor Apache.
![image](https://github.com/user-attachments/assets/4f5a6c0c-1b1a-48a7-ba97-ef2c00ecff63)

Utilitza webmin per aturar Apache.
![image](https://github.com/user-attachments/assets/026eed9b-8d4d-4373-80a1-80bea259fee9)

Utilitza webmin per mostrar l'estat del servidor Apache apagat.
![image](https://github.com/user-attachments/assets/98f98ef2-2ced-48ea-8f90-c0e4279e788d)
![image](https://github.com/user-attachments/assets/83b18dac-d4be-4c78-9af8-4e9b2763c7d3)

Utilitza webmin per reiniciar Apache.
![image](https://github.com/user-attachments/assets/dfe53cca-d39f-4dc3-bb3f-bd5b056bb4e5)

Utilitza webmin per mostrar l'estat del servidor Apache reiniciat.
![image](https://github.com/user-attachments/assets/2128a0c7-46b9-48cf-84a3-eca889a2b927)

5.- Quotes de disc
Activa les quotes de disc pels usuaris amb la comanda:
sudo apt install quota quotatool
![image](https://github.com/user-attachments/assets/7ee2ab0a-b9fb-46c8-ad75-2359cf08d502)
![image](https://github.com/user-attachments/assets/0e34d9f6-79e6-48a2-87c9-e122fd938eb8)


Utilitza webmin perquè l'usuari bakalao_X no pugui tenir més de 2 MB d'informació al disc.
![image](https://github.com/user-attachments/assets/4768ad63-5c5f-40fd-b4f0-828f95c82279)

Comprova que el límit de la quota funciona.
![image](https://github.com/user-attachments/assets/82c672c7-790d-4e53-8038-635608989397)

Utilitza webmin perquè l'usuari techno no pugui tenir més de 10 fitxers al disc.
![image](https://github.com/user-attachments/assets/d29df9b2-4446-48cd-8d00-e22b15850724)

Comprova que el límit de la quota funciona.
![image](https://github.com/user-attachments/assets/1eba54c4-2661-467d-927e-3bf8bb624e48)

6.- Còpies de seguretat
Utilitzant el mòdul de Webmin Filesystem Backup fes una còpia de seguretat del directori /home al directori /backups (l'haureu de crear si no existeix).
![image](https://github.com/user-attachments/assets/2fe7f428-bd34-4c33-9d0d-f0a6e9536375)

Modifica alguns fitxers de /home.
![image](https://github.com/user-attachments/assets/2fe7f428-bd34-4c33-9d0d-f0a6e9536375)
Recupera la còpia de seguretat.
![image](https://github.com/user-attachments/assets/a4ec2d6e-cfc3-4fab-b80e-68d803594b30)

Comprova que els fitxers de /home són els correctes.
![image](https://github.com/user-attachments/assets/a4ec2d6e-cfc3-4fab-b80e-68d803594b30)

Programa una còpia de seguretat de /home/bakalao_X per els divendres a les 21:00.
![image](https://github.com/user-attachments/assets/5d3b312a-8a2a-4469-a733-abb347d874b3)

Esborra la còpia de seguretat programada anteriorment.
![image](https://github.com/user-attachments/assets/89e5d472-4bce-45c5-8432-09aba21fed6d)

7.- Compartició
Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "area_public_X" per a usuaris sense autenticar en forma de lectura i escriptura.
![image](https://github.com/user-attachments/assets/b54298b2-6dc2-4d69-b6db-a0a4f59d12f0)
![image](https://github.com/user-attachments/assets/74e76736-7f80-4485-8d30-fa08f957ca92)

Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "pontaeri_privat_X" per a usuaris _X i techno només de lectura.
![image](https://github.com/user-attachments/assets/fd73f867-e1e6-4de3-9573-cd4c8fd1ddbe)
![image](https://github.com/user-attachments/assets/9b7d857d-9ca9-48ca-acc4-c54f58f425ee)

Comprovar des de Windows que aquests recursos funcionen.
