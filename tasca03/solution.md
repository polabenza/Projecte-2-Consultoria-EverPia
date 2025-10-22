# 🔐 T03: Seguretat Lògica - Recuperant Accés a Sistemes

1. 💻 **Escollim Advanced Options for Zorin**  
2. 🖥️ **Seleccionem `root - Consola de Superusuario`**  
3. 📝 **Posem la següent comanda**  
4. 🔑 **Ara canviem la contrasenya**  
5. 🔄 **Reiniciem la màquina**  
6. 👤 **Ara ja podem accedir a l’usuari i a la terminal o veiem**  
7. 📂 **Obrim el següent arxiu**  
8. 🛡️ **Ara protegirem el GRUB amb la comanda:**  
   ```bash
   grub-mkpasswd-pbkdf2
9. 🖨️ **Ara seguirem amb la comanda grub-mkpasswd | tee salida.txt** 
10. ✏️ **El pas següent serà editar el fitxer /etc/grub.d/40_conf per afegir l'autenticació.**  
11. 🛡️ **Serà en aquest fitxer on necessitarem afegir el hash calculat anteriorment.**
12 .🖊️ **Per això, obrirem l'editor nano però habilitant l'opció multibuffer que permet copiar text d'un fitxer a un altre**
13. ⌨️ **Despres li dones CTRL+R i escrius salida.txt**  
14. 🔄 **Ara per ultim reiniciem i ja estaria** ✅
