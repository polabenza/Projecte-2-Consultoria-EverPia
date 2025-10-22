# 🔐 T03: Seguretat Lògica - Recuperant Accés a Sistemes

1. 💻 **Escollim Advanced Options for Zorin**
 <img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20173924.png?raw=true" />
2. 🖥️ Seleccionem root - Consola de Superusuario

 <img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20173940.png?raw=true" />

3. 📝 **Posem la següent comanda**  
<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20173950.png?raw=true" />

4. 🔑 **Ara canviem la contrasenya**
<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20174001.png?raw=true" />

5. 🔄 **Reiniciem la màquina**
<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20174014.png?raw=true" />

6. 👤 **Ara ja podem accedir a l’usuari i a la terminal o veiem**
<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20174025.png?raw=true" />

7. 📂 **Obrim el següent arxiu**
<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20174036.png?raw=true" />

8. 🛡️ **Ara protegirem el GRUB amb la comanda:**  
   ```bash
   grub-mkpasswd-pbkdf2

<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20174048.png?raw=true" />

9. 🖨️ **Ara seguirem amb la comanda grub-mkpasswd | tee salida.txt**
<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20174116.png?raw=true" />

10. ✏️ **El pas següent serà editar el fitxer /etc/grub.d/40_conf per afegir l'autenticació.**
<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20174128.png?raw=true" />  

11. 🛡️ **Serà en aquest fitxer on necessitarem afegir el hash calculat anteriorment.**
<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20174141.png?raw=true" />

12 .🖊️ **Per això, obrirem l'editor nano però habilitant l'opció multibuffer que permet copiar text d'un fitxer a un altre**

13. ⌨️ **Despres li dones CTRL+R i escrius salida.txt**
<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20174151.png?raw=true" /> 

14. 🔄 **Ara per ultim reiniciem i ja estaria** ✅
<img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20174201.png?raw=true" />
