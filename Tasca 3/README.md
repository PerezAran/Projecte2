# Recuperació d'accés i fortificació de GRUB

## Descripció
Després d'una primera feina exitosa, us arriba un encàrrec urgent: un client ha oblidat la contrasenya d'un portàtil amb **Zorin OS** i cal recuperar l'accés per recuperar documentació important. Per evitar danyar l'equip original, s'ha subministrat **un disc clònic en un disc virtual** perquè hi treballeu.

Primer s'haurà de crear una màquina virtual i connectar-hi el disc clònic. Un cop dins, heu d'identificar l'usuari existent i assignar-li una nova contrasenya. A continuació, el client demana mesures per evitar que es pugui reiniciar la contrasenya fàcilment: cal investigar i aplicar **protecció per contrasenya al GRUB**.

---

## Objectius
1. Crear i arrencar una màquina virtual amb el disc clònic.
2. Accedir al sistema i recuperar/identificar l'usuari existent.
3. Canviar la contrasenya de l'usuari i verificar l'accés.
4. Investigar i aplicar mesures per protegir l'accés al GRUB (protecció amb contrasenya).
5. Documentar tot el procediment amb imatges i fonts.

---

## Material de suport
- Disc virtual (imatge del disc clònic).
- Apunts **RA1AA4 Seguretat Lògica**.
- Article de suport: [Recuperant Password en Linux (WaytoIT)](https://waytoit.wordpress.com/2013/06/06/recuperando-password-en-ubuntu/).

---

## Procediment general (resum)
1. **Crear la màquina virtual**
   - Crear VM (per exemple amb VirtualBox o QEMU).
   - Afegir el disc virtual clònic com a disc primari o secundari segons la configuració.

2. **Arrencar en mode de recuperació / Live**
   - Arrencar la VM des d'un ISO Live (si cal) o utilitzar el mode recovery de GRUB per obtenir shell root.

3. **Muntar la partició i identificar l'usuari**
   - Muntar la partició del sistema de fitxers (ex. `/mnt`).
   - Comprovar el fitxer `/etc/passwd` per veure els comptes d'usuari.
   ```bash
   sudo mount /dev/sdXN /mnt
   cat /mnt/etc/passwd

---

- [Torna a la pàgina principal](/)
- Pots trobar la solucio [Aquí](/Tasca03/solució.md)

