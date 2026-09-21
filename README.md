# 🎨 Generador de Programació Didàctica

**Crea les teves eines didàctiques personalitzades en 5 passos, sense programar.**

Una eina gratuïta i de codi obert per generar programacions didàctiques interactives amb traducció automàtica en català, castellà i anglès.

![Versió](https://img.shields.io/badge/versió-1.0.0-green)
![Llicència](https://img.shields.io/badge/llicència-MIT-blue)
![Idiomes](https://img.shields.io/badge/idiomes-CA%20%7C%20ES%20%7C%20EN-purple)

---

## 📋 Índex

1. [Què és això?](#què-és-això)
2. [Què obtindré?](#què-obtindré)
3. [Començar ràpid](#començar-ràpid)
4. [El generador pas a pas](#el-generador-pas-a-pas)
5. [Les 3 eines generades](#les-3-eines-generades)
6. [Publicar a GitHub Pages](#publicar-a-github-pages)
7. [Flux de treball a l'aula](#flux-de-treball-a-laula)
8. [Preguntes freqüents](#preguntes-freqüents)
9. [Requisits tècnics](#requisits-tècnics)
10. [Crèdits i llicència](#crèdits-i-llicència)

---

## 🎯 Què és això?

És un **generador web** que et permet crear 3 eines didàctiques completament personalitzades per a la teva assignatura, sense necessitat de saber programar:

✅ **Programació Didàctica** - El document oficial de la teva assignatura  
✅ **Planificador de Sessions** - La teva eina de gestió diària  
✅ **Fitxa de l'Alumne** - El diari de treball personal de cada alumne  

Tot en **català, castellà i anglès**, amb colors personalitzats i les teves dades.

---

## 🎁 Què obtindré?

Després d'omplir un formulari de 5 passos, obtindràs **3 fitxers HTML** completament autònoms:


### Característiques de cada fitxer:

| Eina | Característiques |
|------|------------------|
| 📚 **Programació** | CRUD complet, historial, editor JSON, sincronització, traducció CA/ES/EN |
| 📅 **Planificador** | Gestió de sessions, activitats visibles/ocultes, log d'accions |
| 📝 **Fitxa alumne** | Seguiment d'activitats, treball complementari, enviament per email |

---

## 🚀 Començar ràpid

### Opció A: Prova ràpida (5 minuts)

1. **Descarrega** el fitxer `generador.html`
2. **Obre'l** amb doble clic (s'obrirà al teu navegador)
3. **Omple** el formulari amb dades de prova
4. **Prem** "🚀 GENERAR ELS 3 FITXERS"
5. **Obre** els fitxers generats i comprova que funcionen

### Opció B: Ús real (15 minuts)

1. **Descarrega** el fitxer `generador.html`
2. **Omple** el formulari amb les dades reals de la teva assignatura
3. **Genera** els 3 fitxers
4. **Puja'ls** a GitHub Pages (veure [secció corresponent](#publicar-a-github-pages))
5. **Comparteix** l'enllaç amb el teu alumnat

---

## 📝 El generador pas a pas

### Pas 1: Dades bàsiques

Informació general de l'assignatura i del professorat:

- **Nom complet de l'assignatura**: Ex: "Matemàtiques 2n Batxillerat"
- **Nom curt**: Ex: "mat2bat" (s'usarà per als noms dels fitxers)
- **Nivell / Ensenyament**: Ex: "Batxillerat"
- **Curs acadèmic**: Ex: "2026-2027"
- **Caràcter**: Obligatòria o Optativa
- **URL del pla d'estudis**: (opcional) Enllaç al document oficial
- **Nom del professor/a**: El teu nom
- **Títol acadèmic**: Ex: "Professor", "Doctor/a"
- **Correu electrònic**: El teu email (l'usaran els alumnes per enviar-te la fitxa)

💡 **Consell**: El "nom curt" és important perquè determinarà el nom dels fitxers generats. Utilitza un nom sense espais ni caràcters especials.

### Pas 2: Personalització visual

Tria els colors i la icona de les teves eines:

- **Icona principal**: Un emoji que representarà la teva assignatura (ex: 🧮 per mates, 🧪 per química, 📚 per literatura)
- **Color principal i secundari**: Tria els colors manualment o tria un dels 6 temes predefinits:
  - 🟣 Violeta (Humanitats)
  - 🟢 Verd (Ciències)
  - 🔵 Blau (Tecnologia)
  - 🟠 Taronja (Art)
  - 🔴 Vermell (Salut)
  - 🟤 Marró (Història)

### Pas 3: Contingut pedagògic

Defineix el contingut de la teva programació:

- **Descripció**: Breu text que descriu l'assignatura
- **Competències**: Afegeix les competències oficials (ex: CG1, CECI 3)
- **Resultats d'aprenentatge**: Afegeix els resultats (ex: C1, H1, A1)

💡 **Consell**: Pots afegir tantes competències i resultats com necessitis amb el botó "+ Afegir".

### Pas 4: Calendari de sessions

Defineix les sessions de la teva assignatura:

- **Horari habitual**: Ex: "Divendres 12:00-15:00"
- **Sessions**: Afegeix-les manualment o importa-les des d'un CSV

#### 📋 Importar sessions des de CSV (recomanat)

Si tens moltes sessions, és més ràpid preparar-les a Excel:

1. **Prem** "📥 Descarregar exemple" per obtenir un fitxer CSV de mostra
2. **Obre'l** amb Excel o qualsevol editor de text
3. **Omple** les dades seguint el format:4. **Desa** el fitxer com a CSV
5. **Prem** "📂 Seleccionar fitxer CSV" i tria el teu fitxer

Les sessions s'importaran automàticament!

💡 **Format de data**: El sistema accepta dates en format `YYYY-MM-DD` (ex: 2026-10-09) o `DD/MM/YYYY` (ex: 09/10/2026).

### Pas 5: Previsualitzar i generar

Revisa la configuració i genera els fitxers:

1. **Revisa** el resum de la configuració
2. **Previsualitza** com quedaran les 3 eines (amb les pestanyes)
3. **Tria** quins fitxers vols generar:
   - 📥 Generar només programacio.html
   - 📥 Generar només planificador.html
   - 📥 Generar només fitxa_alumne.html
   - 🚀 **GENERAR ELS 3 FITXERS** (recomanat)

Els fitxers es descarregaran automàticament al teu ordinador.

---

## 🛠️ Les 3 eines generades

### 📚 Programació Didàctica

El **document oficial** de la teva assignatura, amb totes les dades, competències i cronograma.

**Funcionalitats:**
- ✏️ Editar seccions i temes
- 📜 Historial de versions (fins a 20 versions)
- ✏️ Editor JSON per a usuaris avançats
- 💾 Exportar/Importar dades
- 🔄 Sincronització amb el planificador
- 🌐 Traducció automàtica CA/ES/EN
- 🖨️ Impressió/PDF optimitzada

**Ús recomanat**: Per tenir el document oficial de l'assignatura sempre actualitzat i accessible.

### 📅 Planificador de Sessions

La teva **eina de gestió diària** per preparar i gestionar cada sessió.

**Funcionalitats:**
- ✏️ CRUD complet de sessions
- 👁️ Activitats visibles/ocultes per a l'alumne
- 📝 Descripció alternativa per a l'alumnat
- 🏷️ Tipus d'activitat (teòrica, pràctica, avaluació, descans, gestió)
- 🔍 Filtres per estat (prevista, realitzada, en pausa, descartada)
- 📜 Log d'accions complet
- 🔄 Sincronització amb la fitxa de l'alumne
- 🌐 Traducció automàtica CA/ES/EN

**Ús recomanat**: Per preparar cada classe amb tot el detall i sincronitzar amb les fitxes dels alumnes.

**Flux de treball:**
1. La professora edita una sessió al planificador
2. Marca quines activitats són visibles per a l'alumnat
3. Prem "🔄 Actualitzar sessió"
4. L'estat canvia a "Realitzada" i s'envia a les fitxes

### 📝 Fitxa de l'Alumne

El **diari de treball personal** de cada alumne.

**Funcionalitats:**
- 👤 Dades personals de l'alumne
- 📅 Selecció de sessió del calendari
- ✅ Seguiment d'activitats (feta/no feta/pendent)
- 📝 Observacions per activitat
- 📚 Treball complementari (previ i posterior)
- 📊 Resum automàtic
- 📜 Historial d'actuacions (multi-dia)
- 📧 Enviament per email a la professora
- 🔄 Sincronització amb el planificador
- 🌐 Traducció automàtica CA/ES/EN

**Ús recomanat**: Cada alumne té la seva pròpia fitxa al seu dispositiu. Al final de cada sessió, pot enviar-la per email a la professora.

**Flux de treball:**
1. L'alumne obre la seva fitxa
2. Omple les seves dades personals
3. Selecciona la sessió del dia
4. Marca l'estat de cada activitat
5. Afegeix observacions
6. Prem "📧 Enviar" per enviar-la a la professora

---

## 🌐 Publicar a GitHub Pages

Per fer les teves eines accessibles online (i que els alumnes puguin accedir-hi des de qualsevol dispositiu), segueix aquests passos:

### 1. Crear un compte a GitHub

Si encara no en tens, crea un compte gratuït a [github.com](https://github.com).

### 2. Crear un repositori

1. Prem el botó **"+"** a dalt a la dreta → **"New repository"**
2. Posa-li un nom (ex: `mat2bat-2026-2027`)
3. Marca **"Public"**
4. Prem **"Create repository"**

### 3. Pujar els fitxers

1. Dins del repositori, prem **"Add file"** → **"Upload files"**
2. Arrossega els 3 fitxers HTML generats
3. A baix, escriu un missatge (ex: "Primera versió")
4. Prem **"Commit changes"**

### 4. Activar GitHub Pages

1. Ves a **"Settings"** (pestanya a dalt)
2. Al menú lateral, prem **"Pages"**
3. A "Source", tria:
   - **Branch**: `main` (o `master`)
   - **Folder**: `/ (root)`
4. Prem **"Save"**

### 5. Accedir a les teves eines

Espera 1-2 minuts i les teves eines estaran disponibles a:

💡 **Consell**: Comparteix només l'enllaç de la **fitxa de l'alumne** amb el teu alumnat. Les altres dues eines són per a tu.

---

## 🏫 Flux de treball a l'aula

### Abans de classe (professora)

1. Obre el **planificador**
2. Revisa i ajusta la sessió del dia
3. Marca quines activitats seran visibles per a l'alumnat
4. Prem **"🔄 Actualitzar sessió"**

### Durant la classe (alumnes)

1. Cada alumne obre la seva **fitxa**
2. Selecciona la sessió del dia
3. Van marcant l'estat de cada activitat
4. Afegeixen observacions si cal

### Després de classe (alumnes)

1. Premen **"📧 Enviar"** per enviar la fitxa a la professora
2. O bé **"➕ Nova Actuació"** si la sessió continua un altre dia

### Seguiment (professora)

1. Rep els emails dels alumnes amb la seva feina
2. Pot consultar el **log d'accions** al planificador per veure qui ha carregat les dades actualitzades

---

## ❓ Preguntes freqüents

### 🔒 Les meves dades estan segures?

**Sí, completament.** Totes les dades es guarden **localment al teu navegador** (localStorage). No s'envien a cap servidor. Si esborres la memòria cau del navegador, es perdran les dades (per això és important fer còpies de seguretat regularment amb el botó "💾 Còpia Automàtica").

### 💾 Com puc fer una còpia de seguretat?

Cada eina té un sistema de còpia de seguretat:
- **Còpia automàtica**: Prem "💾 Còpia Automàtica" i es descarregarà un fitxer JSON
- **Historial de versions**: Automàticament es guarden fins a 20 versions
- **Abans de restablir**: El sistema et preguntarà si vols fer una còpia

### 🌐 Com funciona la traducció?

Cada eina té un **selector d'idioma** (🌐) a la cantonada superior dreta. La traducció és:
- **Automàtica**: No cal connexió a internet
- **Instantània**: Canvia en el moment
- **Memòria compartida**: Si canvies l'idioma en una eina, es manté a les altres

⚠️ **Important**: La traducció només afecta la **interfície** (botons, menús, missatges). El **contingut pedagògic** (descripcions, competències, sessions) es manté en l'idioma original en què l'has escrit.

### 📱 Funciona al mòbil o tauleta?

**Sí**, totes les eines són **responsive** i s'adapten a qualsevol mida de pantalla.

### 🔄 Què passa si tanco el navegador a mig editar?

**No passa res.** Gràcies al guardat automàtic, quan tornis a obrir l'eina, tot estarà exactament com ho havies deixat.

### 📧 Com rebo les fitxes dels alumnes?

Els alumnes utilitzen el botó **"📧 Enviar"** de la seva fitxa. Això obre el seu client de correu amb:
- La teva adreça ja omplerta
- L'assumpte amb el nom de l'alumne i la sessió
- El cos amb un resum de la feina feta

Només han de prémer "Enviar".

### 🎨 Puc canviar els colors després de generar?

**Sí**, però has de tornar a generar els fitxers amb el generador. No hi ha una manera directa de canviar els colors d'un fitxer ja generat (tret que editis el codi HTML manualment).

### 📊 Quants alumnes poden utilitzar la fitxa simultàniament?

**Tants com vulguis.** Cada alumne té la seva pròpia còpia de la fitxa al seu dispositiu. No hi ha límit.

### 🆘 He perdut les meves dades, què faig?

1. **Comprova l'historial de versions**: Prem "⚙️ Més opcions → 📜 Historial" i restaura una versió anterior
2. **Importa una còpia de seguretat**: Si havies exportat les dades prèviament, prem "⚙️ Més opcions → 📤 Importar"
3. **Si no tens còpia**: Malauradament, les dades es deuen haver perdut. És molt important fer còpies regularment.

---

## 💻 Requisits tècnics

### Per utilitzar el generador:
- Un navegador web modern (Chrome, Firefox, Safari, Edge)
- Connexió a internet només per descarregar el generador (després funciona offline)

### Per utilitzar les eines generades:
- Un navegador web modern
- **No cal connexió a internet** (funciona offline)
- JavaScript habilitat (activat per defecte a tots els navegadors)

### Per publicar a GitHub Pages:
- Un compte gratuït a GitHub
- Connexió a internet

---

## 🙏 Crèdits i llicència

### Llicència

Aquest projecte està sota llicència **MIT**, la qual cosa significa que pots:
- ✅ Utilitzar-lo lliurement
- ✅ Modificar-lo
- ✅ Distribuir-lo
- ✅ Fer-ne ús comercial

L'única condició és mantenir l'avís de copyright original.

### Crèdits

Creat amb 💜 per millorar l'educació.

Agraïments especials a:
- Tots els professors i professores que han provat l'eina i han donat feedback
- La comunitat educativa que creu en les eines digitals obertes

### Contribucions

Si vols contribuir al projecte, pots:
- Reportar errors o suggerir millores
- Proposar noves funcionalitats
- Traduir a altres idiomes
- Compartir l'eina amb altres professors

---

## 📞 Suport

Si tens algun problema o pregunta:

1. **Revisa aquesta documentació** (potser la resposta ja hi és)
2. **Comprova les preguntes freqüents** (secció anterior)
3. **Fes una còpia de seguretat** abans de fer canvis importants

---

## 🎉 Comença ara!

[**Descarrega el generador**](generador.html) i crea les teves eines didàctiques en 5 minuts!

---

<div align="center">

**Fet amb 💜 per professors i professores**

*Perquè l'educació mereix eines modernes i accessibles*

</div>
