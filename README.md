# ScenarioGen – Prompt per Esercizi di Prompt Engineering

Prompt di sistema per generare sfide di prompting personalizzate durante il corso.
Basato sul framework: **Ruolo · Obiettivo · Contesto · Formato/Tono · Regole/Vincoli**.

---

## Scopo

- Trasformare un modello generalista in un generatore di scenari realistici e su misura.
- Allenare la scrittura di prompt efficaci attraverso un ciclo in 3 fasi:  
  **Scenario → Tentativo → Feedback**.
- Far emergere i consigli avanzati (CoT, domande chiarificatrici) *dopo* che l'utente ha provato.

---

## Come usarlo

1. Apri una **nuova chat** con il tuo LLM preferito (ChatGPT, Claude, Gemini…).
2. Copia **tutto** il contenuto del file `prompt_scenariogen.md`.
3. Incollalo come **primo messaggio** e premi Invio.
4. Aspetta la domanda iniziale dello strumento, poi rispondi con il tuo ruolo o settore  
   (es. `HR`, `Docente`, `Infermiere`, `Project Manager`).
5. Leggi lo scenario generato e **scrivi il tuo prompt** di risposta.
6. Usa il feedback per migliorare il prompt (max 2 iterazioni).

> ⚠️ Non aggiungere altro testo nel primo messaggio: incolla solo il prompt e aspetta.

---

## A chi è rivolto

- Partecipanti al corso che seguono le **Fasi 1–2–3** del percorso di prompt engineering.
- Professionisti che vogliono applicare gli LLM al proprio contesto lavorativo reale.
- Docenti e formatori che cercano esercizi autentici e facilmente personalizzabili.

---

## Note didattiche

- Il prompt **non fornisce la soluzione**: genera solo lo scenario e la traccia operativa.
- I suggerimenti avanzati (`"Pensa passo passo"`, `"Fai le domande che ti servono…"`)  
  appaiono **solo dopo** che l'utente ha scritto il proprio tentativo di prompt.
- Comandi di iterazione disponibili (senza fare nuove domande):
  - `Rigenera` – varia contesto e artefatti, stessa tipologia
  - `Più difficile` / `Più facile` – aumenta o diminuisce il livello
  - `Più breve` – riduce contesto e vincoli del 30%
  - `Cambia obiettivo: A/B/C` – cambia solo la tipologia di sfida

---

## Condivisione in aula

- Condividi il link **Raw** del file (pulsante `Raw` su GitHub): l'utente vedrà solo testo puro.
- Oppure genera un **QR code** dal link Raw e proiettalo sulla slide.

---

## Changelog

| Data | Modifica |
|------|----------|
| 2026-02-27 | Prima versione rilasciata per il corso |
