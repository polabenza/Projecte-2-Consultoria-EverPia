# 🔐 Recuperació d'accés a Zorin OS i seguretat del sistema

Després de la primera feina exitosa, us arriba un **encàrrec urgent** que obliga a posar-vos-hi per donar-li solució.  

## 🏫 Formació prèvia
Abans de començar, rebreu una formació sobre **seguretat lògica** que us permetrà tenir els coneixements necessaris per afrontar la tasca.

## 👥 Context del client
Ha arribat a la consultora un equip d’un client que demana que solucionem un problema:  
- Té un portàtil amb **Zorin OS** (Linux amb entorn gràfic).  
- L’usuari habitual ha **oblidat la contrasenya**.  
- És necessari recuperar l’accés perquè hi ha **documentació important**.  
- Per evitar qualsevol dany al dispositiu original, s’ha **clonat el disc en un disc virtual** per treballar-hi.

## 💻 Objectius

1. **Crear una màquina virtual** i connectar-hi el disc clonat.  
2. Entrar a la màquina virtual i:
   - Trobar el **nom de l’usuari existent**.
   - Assignar-li una **nova contrasenya**.

3. Informar el client de la senzillesa d’aquest procés.  

> ⚠️ El client té por que, si algú roba el portàtil, pugui accedir a la informació.

4. Investigar **mecanismes de protecció** per evitar que es pugui reiniciar la contrasenya amb el procediment anterior.  
5. Implementar **protecció per contrasenya al GRUB** per evitar canvis de configuració no autoritzats.

## 🛡️ Reptes de seguretat
- Evitar accessos no autoritzats.  
- Protegir informació crítica.  
- Garantir que el GRUB estigui **segur i només accessible per administradors**.
