# ⚡ **Informe tècnic: Selecció d’un SAI per a TecnoGestió S.L.**

---

## 1️⃣ **Inventari d’equips**

**Equipaments a l’empresa:**

* 4 ordinadors de sobretaula
* 4 monitors (1 per ordinador)
* 1 impressora-fotocopiadora multifunció
* 1 router d’accés a Internet

**Dispositius que es connectaran al SAI:**

* Ordinadors (4 unitats)
* Monitors (4 unitats)
* Router (1 unitat)

**Dispositius que no es connectaran al SAI:**

* Impressora-fotocopiadora multifunció

**Justificació:**
La impressora consumeix molta energia i no és crítica durant un tall elèctric. Ordinadors, monitors i router són essencials per garantir la continuïtat del treball.

---

## 2️⃣ **Consum estimat dels dispositius**

| Equip        | Consum (W) | Consum (VA) |
| ------------ | ---------- | ----------- |
| Ordinador    | 150 W      | 188 VA      |
| Monitor LCD  | 30 W       | 38 VA       |
| Router Wi-Fi | 15 W       | 19 VA       |

**Càlcul de potència total:**

* Ordinadors: 4 × 188 VA = 752 VA
* Monitors: 4 × 38 VA = 152 VA
* Router: 19 VA

**Total consumida:** 752 + 152 + 19 = **923 VA**
**Incloent reserva 20%:** 923 × 1,20 = **1.108 VA**

---

## 3️⃣ **Determinació de l’autonomia**

**Autonomia mínima requerida:** 10 minuts (0,167 hores)

**Energia necessària:**
[
Energia = 1.108 \text{ VA} × 0,167 h ≈ 184,9 \text{ VAh}
]

**Tenint en compte eficiència del 85%:**
[
Ebateria = 184,9 / 0,85 ≈ 218 VAh
]

> La bateria del SAI hauria de tenir **mínim 220 VAh** per garantir 10 minuts d’autonomia.

---

## 4️⃣ **Models de SAI analitzats**

| Marca / Model            | Potència        | Autonomia | Sortides | Preu aprox. |
| ------------------------ | --------------- | --------- | -------- | ----------- |
| APC Back-UPS Pro 1500    | 1500 VA / 900 W | 10-12 min | 6        | 230 €       |
| Eaton Ellipse Eco 1300   | 1300 VA / 720 W | 10-15 min | 4        | 190 €       |
| CyberPower CP1500EPFCLCD | 1500 VA / 900 W | 10-12 min | 8        | 210 €       |

---

## 5️⃣ **Selecció final i justificació**

**Recomanació:** **APC Back-UPS Pro 1500 VA**

**Motivació:**

* Potència suficient amb marge respecte al consum total
* Autonomia de 10-12 minuts per guardar treballs i apagar correctament
* Varietat de sortides per tots els equips
* Marca reconeguda amb bon servei tècnic i fiabilitat
* Pantalla LCD per supervisar l’estat del SAI

---

> ✅ **Conclusió:** APC Back-UPS Pro 1500 VA és la millor opció per protegir els equips de TecnoGestió S.L., garantint seguretat, autonomia i facilitat de gestió.
