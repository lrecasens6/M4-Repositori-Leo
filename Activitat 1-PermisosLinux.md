Activitat 1 - chmod
1. Ves al teu directori personal i crea una carpeta anomenada "Exercici-X" on
X és el teu cognom.
![image](https://github.com/user-attachments/assets/a699449b-9630-498c-87fe-3fd2c5da28b0)

2. Canvia els permisos del directori perquè només el propietari tingui tots els
permisos.
![image](https://github.com/user-attachments/assets/23dde014-01ef-44de-9e40-9f99687be1a2)
![image](https://github.com/user-attachments/assets/5b52965d-6a83-4922-94f5-806136827d30)

4. Crea un arxiu anomenat "arxiu1.txt" dins del directori anterior i verifica els
permisos. ![image](https://github.com/user-attachments/assets/b1fbe86a-8ad4-4ed6-bc20-6a70b4c32b77)

5. Crea un grup anomenat "proves". ![image](https://github.com/user-attachments/assets/f6287251-2dab-4218-84f2-53c8f9ef191f)

6. Dona-li permisos de lectura i escriptura sobre "arxiu1.txt" al grup. ![image](https://github.com/user-attachments/assets/b01f8b16-bf0e-4cbd-975b-1cdc19ec1fd3)

7. Crea un subdirectori anomenat "sub-X" on X és el teu cognom. ![image](https://github.com/user-attachments/assets/d8d56ea6-5d3e-4bbb-93c4-705bb41e1dab)

8. Deixa el subdirectori anterior amb permisos només per al propietari (rwx). ![image](https://github.com/user-attachments/assets/a081f3e8-d6c5-430f-8551-50ee16f63188)

9. Concedeix permisos d'execució al grup "proves" sobre "sub-X". ![image](https://github.com/user-attachments/assets/871ed686-e613-4264-94a9-3bb06e5253a3)

10. Crea un usuari anomenat "convidat". ![image](https://github.com/user-attachments/assets/633982ab-e4b3-4865-9f8f-53f47ed32489)

10.Canvia els permisos del directori "Exercici-X" perquè l'usuari "convidat"
pugui accedir. ![image](https://github.com/user-attachments/assets/cc11eae7-eed2-4d97-b820-deebc5a14ec9)
![image](https://github.com/user-attachments/assets/61c5d297-2aa1-4a61-aa27-760887c9b070)

11.Canvia els permisos de l'arxiu "arxiu1.txt" perquè tots els usuaris tinguin
només permís de lectura. ![image](https://github.com/user-attachments/assets/3452afd3-716e-495a-ac39-8e64c297e888)

12.Comprova que l'usuari "convidat" no pot accedir al subdirectori "sub-X". ![image](https://github.com/user-attachments/assets/6accead9-12da-4613-9f5e-e617f9a82ab2)

13. Afegeix convidat al grup "proves" i comprova que sí té accés a "sub-X". ![image](https://github.com/user-attachments/assets/bc9448bb-26b3-4ad7-8bae-e2bda2af9495)

(POTSER NECESSITES REINICIAR EL SISTEMA).


Activitat 2 – umask
1. Crea un usuari anomenat "proves2" i mostra la seva màscara per defecte.
2. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-r--r-- i els
directoris amb rwxr-xr-x.
3. Comprova que la màscara anterior funciona.
4. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-rw-rw- i
els directoris amb rwxrwxrwx.
5. Comprova que la màscara anterior funciona.
6. Modifica la màscara de proves2 perquè els fitxers els crei amb r--r--r-- i els
directoris amb r-xr-xr-x.
7. Comprova que la màscara anterior funciona.
8. Modifica la màscara de proves2 perquè els fitxers els crei amb rw--w--w- i
els directoris amb rwx--x--x.
9. Comprova que la màscara anterior funciona.
10.Modifica la màscara per crear un fitxer anomenat "511.txt" amb permisos r-
-------
11.Utilitza chmod perquè els permisos de "511.txt" siguin r-x--x--x.
12.Utilitza chmod perquè el fitxer anterior tingui permisos rwxrwxr-x.
13.Utilitza chown perquè el fitxer anterior sigui propietat de l'usuari root i del
grup proves.
14. Intenta eliminar el fitxer amb l'usuari proves2. (sense sudo)
15. Afegeix l'usuari proves2 al grup proves i elimina el fitxer anterior.
