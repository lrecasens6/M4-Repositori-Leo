Activitat 1: Crea i explica les comandes per fer còpia de seguretat i restaurar el
directori /var/www amb la comanda tar.
-c: Crear un arxiu nou
-z: Comprimir amb gzip
-v: Mode verbose (mostra arxius processats)
-f: Especificar nom de l'arxiu de destinació

• sudo tar -czvf /home/xavi/mohaguapo.tar /var/www
![image](https://github.com/user-attachments/assets/761e44a5-a018-46aa-b69a-0a7102a66adc)

• sudo tar -xzvf /home/xavi/mohaguapo.tar -C /
![image](https://github.com/user-attachments/assets/4037bab0-c692-47a5-ac78-d8cd63fdd977)

Activitat 2: Crea i explica les comandes per fer còpies de seguretat i restaurar el
directori /var/www amb la comanda rsync.
![image](https://github.com/user-attachments/assets/78337457-560b-4802-adf8-c759545bd33c)
-a: Mode arxiu (preserva permisos, propietaris, timestamps, etc.)
-v: Mode verbose (mostra detalls de la còpia)
-z: Comprimeix les dades durant la transferència

Activitat 3: Utilitzant els comandaments de Dump i restore:
• Crea una carpeta al teu home anomenada /Xbackup.
![image](https://github.com/user-attachments/assets/2cb098eb-2c5c-43a0-a4e7-2144d2defe83)

• Dins la carpeta guarda dues imatges.
![image](https://github.com/user-attachments/assets/c4d43fd5-1b06-48dc-9185-394ecfc0b8d3)

• Fes un backup amb dump al fitxer /tmp/Xbackup de la carpeta.
![image](https://github.com/user-attachments/assets/7801eb27-fb50-4bda-b39d-760cee997f46)

• Esborra les imatges.
![image](https://github.com/user-attachments/assets/1e86cbc4-ecc3-46b9-b4da-43c7d61f94b4)

• Recupera amb restore les imatges a la carpeta que ara està buida.
![image](https://github.com/user-attachments/assets/5642f1f6-4bee-4b05-9359-a186d19231a2)

Activitat 4: repeteix l’activitat anterior amb tar.
![image](https://github.com/user-attachments/assets/1da11746-f722-451e-9ca4-feff5d44b22b)

Activitat 5: Repeteix l’activitat anterior amb rsync.
![image](https://github.com/user-attachments/assets/47e0f8b0-b216-4d94-b7c9-4afd6e865c8f)

Activitat 6: Utilitza deja-dup per fer una còpia de seguretat del teu directori
/home/usuari
![image](https://github.com/user-attachments/assets/7e1376e7-0f24-49e3-8ed8-3412f29657b3)
![image](https://github.com/user-attachments/assets/2a625e1c-7154-488c-bbde-856110a445aa)
![image](https://github.com/user-attachments/assets/b0123374-7f6e-4057-8af2-6ca1964adf90)
![image](https://github.com/user-attachments/assets/8a44b71f-c66e-478e-a073-9c36dceabe5a)
![image](https://github.com/user-attachments/assets/d7d9dc02-549c-4425-a0e3-1519c114834a)
![image](https://github.com/user-attachments/assets/fb56c03b-b602-4567-b24d-8c4770b9b288)

Activitat 7: Busca un altre programa de backups en entorn gràfic i fes una copia de
seguretat de /home/usuari. Documenta el procés.
Instal·lar Grsync: ![image](https://github.com/user-attachments/assets/a47715da-33a7-42e5-9c19-216e8248bca9)
Obrir Grsync: ![image](https://github.com/user-attachments/assets/b14c525e-1683-441b-bd4e-53af7f3f8f71)
Configuració de la còpia de seguretat: ![image](https://github.com/user-attachments/assets/5d86241c-edb0-4410-b692-52a4601c02bf)
 Realitzar la còpia de seguretat:![image](https://github.com/user-attachments/assets/4f5af31a-ed86-42db-b636-2d28964c561d)
