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


5. Amb la comanda htop mostra el percentatge de la memòria utilitzada.

6. Utilitzant gnome-system-monitor mostra:
• El procés que utilitza més memòria.
• El procés que utilitza més CPU.
• Obre el programa calculadora i busca'l.
• Indica el seu PID.
• Mata el procés.
• Amb el monitor de recursos mostra l'activitat de xarxa.
• Amb Sistema de fitxers mostra l'espai lliure a /home.
• mostra l'espai lliure a l'arrel del sistema.
• Canvia les preferències per que els processos s'actualitzin cada 2
segons i per que mostri l'estat d'execució dels processos.
• Busca els processos que estan en estat d'execució i mostra'ls.

7. Monitoratge:
• Crea la carpeta /prova
• Busca a /var/log/auth.log l'esdeveniment on es registra que has creat la
carpeta.
• Elimina-la.
• Busca l'esdeveniment on es registra que l'has eliminat.
• Inicialitza gedit.
• Busca a /var/log/syslog el registre d'obertura de gedit.
• Crea un registre que digui "Marca de X al registre" on X és el teu cognom.
• Busca el registre i mostra'l.
• Mostra els registres d'error de dmesg.
• Mostra de forma gràfica els registres d'aplicacions del sistema.
• Obre una aplicació i mostra el registre a l'aplicació gràfica.
