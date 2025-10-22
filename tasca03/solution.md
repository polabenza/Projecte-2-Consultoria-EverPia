# 🔐 T03: Seguretat Lògica - Recuperant Accés a Sistemes

1. 💻 **Escollim Advanced Options for Zorin**
 <img src="https://github.com/polabenza/Projecte-2-Consultoria-EverPia/blob/main/tasca03/img/Captura%20de%20pantalla%202025-10-22%20173924.png?raw=true" />
3. 🖥️ **Seleccionem `root - Consola de Superusuario`**  
4. 📝 **Posem la següent comanda**  
5. 🔑 **Ara canviem la contrasenya**  
6. 🔄 **Reiniciem la màquina**  
7. 👤 **Ara ja podem accedir a l’usuari i a la terminal o veiem**  
8. 📂 **Obrim el següent arxiu**  
9. 🛡️ **Ara protegirem el GRUB amb la comanda:**  
   ```bash
   grub-mkpasswd-pbkdf2
10. 🖨️ **Ara seguirem amb la comanda grub-mkpasswd | tee salida.txt** 
11. ✏️ **El pas següent serà editar el fitxer /etc/grub.d/40_conf per afegir l'autenticació.**  
12. 🛡️ **Serà en aquest fitxer on necessitarem afegir el hash calculat anteriorment.**
12 .🖊️ **Per això, obrirem l'editor nano però habilitant l'opció multibuffer que permet copiar text d'un fitxer a un altre**
13. ⌨️ **Despres li dones CTRL+R i escrius salida.txt**  
14. 🔄 **Ara per ultim reiniciem i ja estaria** ✅
