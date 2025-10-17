
**Figura:** Escollim *Advanced Options for Zorin*

---

## 🛠️ Menú de recuperació

Seleccionem `root` – Consola de Superusuari

**Figura:** Menú de recuperación (estado del sistema de archivos: solo lectura)

### Opcions disponibles:

| Comanda          | Descripció                                      |
|------------------|--------------------------------------------------|
| `resume`         | Continuar amb l'arrencada normal                |
| `clean`          | Intentar alliberar espai                        |
| `dpkg`           | Reparar paquets trencats                        |
| `fsck`           | Revisar tot el sistema de fitxers               |
| `grub`           | Actualitzar el carregador d'arrencada grub     |
| `network`        | Activar la xarxa                                |
| `root`           | Consola de superusuari                          |
| `system-summary` | Resum del sistema                               |

---

## 🔐 Recuperació de contrasenya

```bash
root@laptop:~# mount -o remount,rw /
root@laptop:~# ls /home
miquel
root@laptop:~# passwd miquel

