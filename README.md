# 🩺 XAI Chest X-Ray with Grad-CAM

Repository per lo sviluppo di Explainable AI (XAI) applicata alle radiografie toraciche.
Include notebook per il training del modello e per la spiegabilità con Grad-CAM,
modello salvato (.h5), immagini di test e un template di report clinico in Markdown
per radiologi e pazienti.

---

## 📊 Risultato del modello
- **Diagnosi AI:** Pneumonia
- **Probabilità:** 0.87 (87%)

## 🔎 Interpretazione per Radiologo
Il modello ha identificato aree polmonari con opacità compatibili con polmonite.  
La heatmap Grad‑CAM evidenzia le zone che hanno influenzato maggiormente la decisione.  
Il radiologo può verificare se l’AI si è concentrata su regioni patologiche o su artefatti.

## 🧑‍⚕️ Spiegazione semplificata per Paziente
L’analisi dell’AI suggerisce la presenza di polmonite.  
La mappa colorata mostra le zone dei polmoni che hanno portato a questa conclusione.  
Questa analisi **non sostituisce la valutazione medica**, ma supporta il medico nella diagnosi.

---

## 📂 Struttura del Repository
