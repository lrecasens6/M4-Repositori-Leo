1. Utilitza la comanda free i busca quanta memòria lliure té el sistema, indicala.
![image](https://github.com/user-attachments/assets/59646d45-901f-475e-9d2d-cc9391fa0777)

2. Obre Firefox i busca i indica la memòria lliure del sistema
![image](https://github.com/user-attachments/assets/a59b6d48-6080-49d6-9678-7efacc4c1e9d)

3. Amb la comanda mpstat indica quanta capacitat de CPU està lliure i
quantes CPUs té el sistema.
![image](https://github.com/user-attachments/assets/e7122088-daa3-456e-87fb-03dcd515b2fa)

4. Obre Firefox i utilitza la comanda top i fes una captura, sobre la captura fes
el següent:

![image](https://github.com/user-attachments/assets/2cba6ce6-aebc-4484-98d4-909874200db1)

• Indica si el sistema està més carregat ara que fa cinc minuts o menys
carregat, justifica per què?
Per determinar si el sistema està més o menys carregat, n'hi ha que mirar els valors de load average a dalt de tot:
Si el valor a 1 minut és més alt que a 5 minuts → Sistema més carregat ara
Si el valor a 1 minut és més baix que a 5 minuts → Sistema menys carregat

![image](https://github.com/user-attachments/assets/53ca96ff-83e1-4b03-953b-cd4367123010)

• Busca el PID del procés Firefox.
![image](https://github.com/user-attachments/assets/f8101c2e-00e8-43d4-9d0c-c285525f76f2)

• Mata el procés firefox des de top.
![image](https://github.com/user-attachments/assets/044d97b1-a5de-475e-b206-19e9ce2a3e76)

• Indica quanta memòria d'intercanvi està utilitzant el sistema.
![image](https://github.com/user-attachments/assets/72109215-bbe5-4f57-a2c6-acb6a8aeeeb9)

• Indica quants processos tens oberts i quants estan en execució en
aquest moment.
![image](https://github.com/user-attachments/assets/c4eadaf9-7c97-47bd-83e9-cd2356454b8a)

• Torna a obrir Firefox i mostra el procés amb la ruta a l'executable del
programa.
![image](https://github.com/user-attachments/assets/8cd68c30-051e-4743-ba94-ee113cb87f5a)

5. Amb la comanda htop mostra el percentatge de la memòria utilitzada.
![image](https://github.com/user-attachments/assets/3ece55e9-2d91-4738-9c7a-e55293803007)

6. Utilitzant gnome-system-monitor mostra:
• El procés que utilitza més memòria.
![image](https://github.com/user-attachments/assets/edb85bfd-9d97-465f-a4eb-723430b4c617)

• El procés que utilitza més CPU.
![image](https://github.com/user-attachments/assets/499935f9-0bf5-4ecf-81c1-e87e51ddf899)

• Obre el programa calculadora i busca'l.
![image](https://github.com/user-attachments/assets/aa88eb05-d2c3-4a1e-a938-92f5722d34ef)

• Indica el seu PID.
![image](https://github.com/user-attachments/assets/3decc0a1-fc51-4ab8-8452-a7c399d25b98)

• Mata el procés.
![image](https://github.com/user-attachments/assets/8df5bc20-a93a-484f-9163-d673392c6b39)

• Amb el monitor de recursos mostra l'activitat de xarxa.
![image](https://github.com/user-attachments/assets/1e477cec-5c2d-4bb2-8da7-a22d2a2ac4fc)

• Amb Sistema de fitxers mostra l'espai lliure a /home.
![image](https://github.com/user-attachments/assets/b3d5410f-e056-4080-bf05-54d9980b3c0f)

• mostra l'espai lliure a l'arrel del sistema.
![image](https://github.com/user-attachments/assets/be00dbe7-2ad6-420e-b3f7-c4ea966be30b)

• Canvia les preferències per que els processos s'actualitzin cada 2
segons i per que mostri l'estat d'execució dels processos.
![image](https://github.com/user-attachments/assets/3672d90c-1042-41cb-ba50-3a45e645f77c)

• Busca els processos que estan en estat d'execució i mostra'ls.
![image](https://github.com/user-attachments/assets/fd85094e-a6f0-4ed2-940c-f58d04816793)

7. Monitoratge:
• Crea la carpeta /prova
![image](https://github.com/user-attachments/assets/5b621801-247d-4988-8137-a7e537b326c3)

• Busca a /var/log/auth.log l'esdeveniment on es registra que has creat la
carpeta.
![image](https://github.com/user-attachments/assets/66f3b0c6-c76a-41d9-a2ef-055200ffbe58)

• Elimina-la.
![image](https://github.com/user-attachments/assets/a877dff0-6719-42ea-a3b8-9172127add48)

• Busca l'esdeveniment on es registra que l'has eliminat.
![image](https://github.com/user-attachments/assets/b252d76d-2db1-4500-bfec-031d01fc3394)

• Inicialitza gedit.
![image](https://github.com/user-attachments/assets/363956e5-3347-4673-98bf-5c18fe52eec4)

• Busca a /var/log/syslog el registre d'obertura de gedit.
![image](https://github.com/user-attachments/assets/abf90cda-ef68-45b2-a446-4002c3554baa)

• Crea un registre que digui "Marca de X al registre" on X és el teu cognom.
nano![image](https://github.com/user-attachments/assets/43cfd581-b6d2-499d-92c9-cc6d7aab3fa9)

• Busca el registre i mostra'l.
![image](https://github.com/user-attachments/assets/66935b8b-e406-4792-881e-a488671bd45b)

• Mostra els registres d'error de dmesg.
![image](https://github.com/user-attachments/assets/d493381e-ff1b-487c-b8ce-caa06584364e)

• Mostra de forma gràfica els registres d'aplicacions del sistema.
![image](https://github.com/user-attachments/assets/4c7c7b01-7aab-4535-a142-e9bb3ad978ad)

• Obre una aplicació i mostra el registre a l'aplicació gràfica.
![image](https://github.com/user-attachments/assets/1a3ba861-52d5-4d38-bfaa-bdf87039e642)

