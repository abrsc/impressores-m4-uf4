IMPRESSORES
Activitat 1: vista de Linux.
1. Hem creat una impressora amb cups i configurat cups seguint [aquest tutorial](https://github.com/XaSaFa/MP04/blob/main/uf3/compartir_impresora_linux.md) de l'apartat 1 a 5. <br>
![alt text](image.png)
2. Hem instal·lat Samba: <br>
![alt text](image-1.png)
3. Hem editat la configuració de Samba per compartir les impressores del sistema: <br>
![alt text](image-2.png)
4. Hem reinciat samba: <br>
![alt text](image-3.png)
5. Aqui veiem la pàgina de prova rebuda de Windows. <br>
![alt text](image-4.png)

Activitat 2: vista de Linux.
1. Hem instal·lat smbclient. <br>
![alt text](image-6.png)
2. Hem obert localhost:631 (cups) al ordenador en administració. <br>
![alt text](image-5.png)
3. Hem fet "Add Printer" i sel·leccionat "Windows Printer via SAMBA". <br>
![alt text](image-7.png)
4. Hem ficat la IP, usuari contrasenya i nom de impressora de la màquina Windows. <br>
![alt text](image-8.png)
5. Hem ficat un nom a la impressora. <br>
![alt text](image-9.png)
6. Hem ficat el model i afegit la impressora. <br>
![alt text](image-13.png)
![alt text](image-11.png)
7. Aquí imprimem una pàgina de prova. <br>
![alt text](image-15.png)
8. Al cups veiem que se ha imprimit. <br>
![alt text](image-10.png)
