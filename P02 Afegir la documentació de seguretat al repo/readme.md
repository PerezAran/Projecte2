# P02: Afegint la documentació de seguretat al repositori

## 📝 Breu Descripció
Al llarg d’aquest projecte heu estat documentant una sèrie de guies tècniques. No obstant això, tenir la documentació aïllada en fitxers tradicionals genera un problema organitzatiu anomenat **data silo** (silos de dades), que dificulta l'accés i la col·laboració. 

Per evitar-ho, aprofitarem l'ús del control de versions (**Git i GitHub**) per centralitzar, organitzar i estructurar tota la documentació tècnica del projecte utilitzant el format **Markdown**.

---

## 🎯 Objectius Específics
* Centralitzar la documentació tècnica de seguretat en un entorn professional i accessible.
* Evitar la fragmentació de la informació (*data silos*).
* Dominar el llenguatge de marcatge **Markdown** per a la creació de memòries tècniques atractives i estructurades.
* Implementar bones pràctiques en la gestió de repositoris (estructures de carpetes, rutes relatives i accessibilitat).

---

## 🛠️ Requisits i Desenvolupament de la Tasca

### 1. Configuració del Repositori Principal
* Crear un nou repositori públic a GitHub anomenat exactament: `Projecte2`.
* Crear un fitxer `README.md` a l'arrel que presenti el projecte de manera global. 
  * *Nota: Utilitzeu de forma avançada els recursos de Markdown (negretes, llistes, taules, blocs de codi, etc.) per fer la descripció visualment atractiva i professional.*

### 2. Estructura de Carpetes i Navegació
Dins del repositori s'ha de crear una estructura indexada per a les tasques anteriors:
* Crear una carpeta específica per a la **Tasca 2** i una altra per a la **Tasca 3**.
* Dins de **cada carpeta** hi ha d'haver:
  * Un fitxer `README.md` que expliqui breument l'activitat i el contingut de la carpeta.
  * Aquest `README.md` ha d'incloure obligatòriament un **hipervincle (enllaç)** que dirigeixi l'usuari directament al fitxer `solucio.md`.
  * Una carpeta anomenada `img` per emmagatzemar de forma ordenada els recursos visuals.

### 3. Gestió d'Imatges (`/img`)
* Totes les captures de pantalla s'han de pujar a la seva respectiva carpeta `img`.
* **Formats i mida:** Han d'estar en format `.png` i tenir unes dimensions adequades que no trenquin el disseny de la pàgina.
* **Accessibilitat:** És obligatori que tots els vincles d'imatge continguin una **descripció alternativa (alt text)** clara per a lectors de pantalla o errors de càrrega.

### 4. Documentació de la Solució (`solucio.md`)
* Crear un fitxer anomenat exactament `solucio.md` dins de cadascuna de les carpetes de les tasques (T2 i T3).
* En aquest fitxer es redactarà i documentarà tota la resolució tècnica de la tasca en format Markdown, integrant les imatges de la carpeta `img` mitjançant rutes relatives.

---

## 📂 Estructura de Directoris Esperada

```text
Projecte2/
├── README.md               <-- Presentació global del Projecte 2
├── Tasca2/
│   ├── README.md           <-- Explicació de la T2 + Enllaç a solucio.md
│   ├── solucio.md          <-- Documentació de la solució de la T2
│   └── img/
│       └── captura1.png    <-- Captures amb text alternatiu
└── Tasca3/
    ├── README.md           <-- Explicació de la T3 + Enllaç a solucio.md
    ├── solucio.md          <-- Documentació de la solució de la T3
    └── img/
        └── captura2.png