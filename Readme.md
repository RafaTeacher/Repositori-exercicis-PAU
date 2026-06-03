# Repositori d'exercicis PAU — Tecnologia i Enginyeria (Catalunya)

Recull classificat dels exercicis de les Proves d'Accés a la Universitat (PAU) de la matèria **Tecnologia i Enginyeria** de Catalunya, des del 2016 fins al 2025.

---

## Per a qui és útil

Aquest repositori està pensat principalment per a **alumnes que es preparen per a les PAU** de Tecnologia i Enginyeria. En lloc d'haver de buscar exercicis per any i convocatòria, aquí pots accedir directament a tots els exercicis d'un tema concret, de tots els anys alhora.

---

## Com funciona

L'índex principal (`index.html`) organitza tots els exercicis per **categoria temàtica**:

- Electricitat DC
- Electricitat AC
- Electrònica digital
- Energia · Potència · Mecanismes
- Matemàtiques aplicades
- Materials · Propietats i assaigs
- Metrologia i normalització
- Motors · Generadors elèctrics
- Pneumàtica i Hidràulica
- Sòlid-rígid (estàtica de màquines)
- Termodinàmica

Cada exercici inclou un resum de l'enunciat i un enllaç directe al PDF de l'examen (preguntes) i al PDF de les solucions. A més, per a cada any i convocatòria hi ha un fitxer de classificació individual que mostra tots els exercicis d'aquell examen amb la seva categoria.

Hi ha també un formulari de referència (`formules.html`) amb les fórmules principals organitzades per categoria, amb explicació de variables i consells pràctics.

---

## Com navegar pels PDFs

Els enllaços dels exercicis obren el PDF a la **pàgina aproximada** on comença l'exercici. Aquesta pàgina pot contenir més d'un exercici, de manera que **l'usuari ha de localitzar visualment l'exercici dins de la pàgina**.

### Problema amb Chrome i extensions de PDF

Si fas servir **Google Chrome** amb l'extensió d'Adobe Acrobat Reader instal·lada, és possible que els PDFs s'obrin sempre per la primera pàgina, ignorant la pàgina indicada a l'enllaç. Això és un problema causat per l'extensió, que intercepta l'obertura del PDF abans que el navegador pugui processar el número de pàgina.

**Solucions:**
- Utilitza **Mozilla Firefox** o **Microsoft Edge**, que no presenten aquest problema.
- O bé desactiva l'extensió d'Acrobat a Chrome: `chrome://extensions` → localitza Adobe Acrobat → desactiva-la.

---

## Errors i suggeriments

Si trobes un error (enllaç incorrecte, exercici mal classificat, pàgina de PDF errònia...), 
obriu una Issue a GitHub:

👉 [Reportar un error](https://github.com/rafateacher/Repositori-exercicis-PAU/issues/new)

Indica el nom de l'exercici, la categoria on apareix i una breu descripció del problema.

---

## Estat del projecte

Aquest repositori és un **treball en curs**, elaborat majoritàriament amb l'ajuda d'**intel·ligència artificial** (classificació d'exercicis, generació dels fitxers HTML i actualització de l'índex). Tot i que s'ha revisat el resultat, és possible que hi hagi errors de classificació, referències incorrectes o exercicis mal assignats.

Qualsevol correcció o suggeriment és benvingut.

---

## Contingut actual

- **Anys coberts:** 2016 – 2025
- **Convocatòries:** juny i setembre de cada any
- **Exercicis únics indexats:** 288
- **Fitxers de classificació individuals:** un per cada sèrie d'examen

---

## Estructura de fitxers

Repositori-exercicis-PAU/
├── index.html                            ← índex principal per categories
├── formules.html                         ← formulari de referència
├── PAU_Juny_AAAA_SerieX_classificacio.html
├── PAU_Setembre_AAAA_classificacio.html
└── pdfs/
├── Examen_de_Tecnologia_Industrial_Juny_AAAA.pdf
├── Examen_de_Tecnologia_Industrial_Juny_AAAA_Solucions.pdf
├── Examen_de_Tecnologia_Industrial_Setembre_AAAA.pdf
└── Examen_de_Tecnologia_Industrial_Setembre_AAAA_Solucions.pdf
---

*Els PDFs dels exàmens i les solucions oficials són propietat del Consell Interuniversitari de Catalunya i es referencien aquí únicament amb fins educatius.*