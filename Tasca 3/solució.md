# Pas a Pas  
## SEGURETAT LÒGICA

---

**Fet per:** Aran Perez

---

## Configuració de la màquina:

Al primer que haurem de fer serà crear una màquina virtual sense res, només posant el nom, la ruta, i configurar-la com a tipus Linux.

![foto](img/1.jpg)

Un cop fet això, anem a **Emmagatzematge** i afegim el disc dur que ens hem descarregat:  
`p02t03-disk1.vmdk`

![foto](img/imatge_2.1.jpg.png)

I ara només faltarà configurar la màquina com ens demana.

![foto](img/imatge_4.jpg)

---

## Canviar password:

Ara, un cop arranquem la màquina, hem de mantenir premut **Shift** i una lletra qualsevol.  
Ens sortirà aquesta primera opció: li donarem a **“Advanced options…”**

![foto](img/imatge_5.jpg)

En el següent menú, haurem de donar-li a la segona opció.

![foto](img/imatge_6.jpg)

Al menú de recuperació, triarem l'opció **root**.

![foto](img/imatge_7.jpg)

Ara haurem de teclejar la següent comanda:  

(miquel és el nom d'usuari) i posar la nova contrasenya.

![foto](img/imatge_8.jpg)

---

## Investigar com es pot fortificar l'accés al GRUB:

Llocs web que m'han ajudat: *link*


Fem un: **sudo -i** per entrar com a root.

![foto](img/imatge_9.jpg)

Ara hem instal·lat al GRUB i li hem posat una contrasenya.

![foto](img/imatge_10.jpg)

(Ara copiarem tot el hash des de `grub` fins al final)

Ara haurem de posar el nom d'usuari i la contrasenya (la contrasenya serà el hash). Això ho posarem a la ruta: **/etc/grub.d/40_custom**  

![foto](img/imatge_11.jpg)

I per acabar farem un **sudo grub-mkconfig -o /boot/grub/grub.cfg** per aplicar els canvis del GRUB.

![foto](img/imatge_12.jpg)

A l'hora d'entrar surt aquest panell.

![foto](img/imatge_13.jpg)





