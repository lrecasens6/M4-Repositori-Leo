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
1. Crea un usuari anomenat "proves2" i mostra la seva màscara per defecte. ![image](https://github.com/user-attachments/assets/80705ca8-4f53-4f6f-84ab-0b5d55a26ba7)

2. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-r--r-- i els
directoris amb rwxr-xr-x. ![image](https://github.com/user-attachments/assets/b383f676-4369-40b2-b013-c252d5ab0957)

3. Comprova que la màscara anterior funciona. ![image](https://github.com/user-attachments/assets/f652b958-2eef-4566-9c18-48fa4d11337b)

4. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-rw-rw- i
els directoris amb rwxrwxrwx. ![image](https://github.com/user-attachments/assets/173f6b53-67c7-45cd-8b02-d4ecd623f1bd)

5. Comprova que la màscara anterior funciona. ![image](https://github.com/user-attachments/assets/cd1e765d-35c9-462f-80a8-eabafde61b3d)

6. Modifica la màscara de proves2 perquè els fitxers els crei amb r--r--r-- i els
directoris amb r-xr-xr-x. ![image](https://github.com/user-attachments/assets/546a7e71-d4e7-4c90-82e5-fe2b8fe528b5)


7. Comprova que la màscara anterior funciona. 
![image](https://github.com/user-attachments/assets/5a35cf15-d97a-4188-817d-1f216f9f1e7f)

8. Modifica la màscara de proves2 perquè els fitxers els crei amb rw--w--w- i
els directoris amb rwx--x--x. ![image](https://github.com/user-attachments/assets/21cc76d1-e5a9-49b1-881d-9425b77ebd8f)

9. Comprova que la màscara anterior funciona. ![image](https://github.com/user-attachments/assets/0cc46e91-266a-4c6b-b7b2-eec8d51a2b9a)

10.Modifica la màscara per crear un fitxer anomenat "511.txt" amb permisos r-
------- ![image](https://github.com/user-attachments/assets/44231581-3d7a-4f19-8947-ee423f24c6be)

11.Utilitza chmod perquè els permisos de "511.txt" siguin r-x--x--x. ![image](https://github.com/user-attachments/assets/656487db-1396-4d89-9df2-7704e6bb2cdb)

12.Utilitza chmod perquè el fitxer anterior tingui permisos rwxrwxr-x. ![image](https://github.com/user-attachments/assets/cd232f87-2767-4f7c-a382-0d05dd22865e)

13.Utilitza chown perquè el fitxer anterior sigui propietat de l'usuari root i del
grup proves. ![image](https://github.com/user-attachments/assets/ca87ce1f-b48f-4183-ad87-5b6d5ce101f5)

14. Intenta eliminar el fitxer amb l'usuari proves2. (sense sudo) ![image](https://github.com/user-attachments/assets/5b17e92c-3de4-4957-8671-2beecad16d59)

15. Afegeix l'usuari proves2 al grup proves i elimina el fitxer anterior. ![Uploading image.png…]()

