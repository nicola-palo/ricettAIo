# RicettAIo 🍳

RicettAIo è una semplice e moderna applicazione web che genera ricette a partire da una lista di ingredienti, utilizzando la potenza dell'API di Google Gemini.

![Screenshot dell'applicazione RicettAIo](https://via.placeholder.com/800x400.png?text=Interfaccia+di+RicettAIo)

*Suggerimento: Sostituisci l'URL sopra con un link a uno screenshot reale della tua applicazione una volta caricata su GitHub.*

---

## ✨ Funzionalità

- **Generazione di Ricette AI**: Inserisci gli ingredienti che hai a disposizione e ottieni una ricetta creativa e deliziosa generata dal modello Gemini 1.5 Flash.
- **Layout Dinamico e Moderno**: L'interfaccia si trasforma da una singola vista centrata a un layout a due colonne dopo la generazione della ricetta.
- **Rendering Markdown**: Le ricette sono formattate in modo chiaro e leggibile (titoli, liste, grassetto) per una facile consultazione.
- **Esperienza Utente Curata**: L'applicazione è fissa sulla finestra del browser, con scorrimento dedicato solo all'area della ricetta, per un feeling da vera web-app.
- **Gestione Stati**: Interfaccia reattiva con indicatori di caricamento animati e messaggi di errore chiari.

## 🛠️ Tecnologie Utilizzate

- **Frontend**: [React](https://reactjs.org/) (Componenti Funzionali e Hooks `useState`, `useEffect`)
- **API**: [Google Gemini API](https://ai.google.dev/)
- **Styling**: CSS3 moderno (Flexbox, Animazioni @keyframes)
- **Markdown**: [react-markdown](https://github.com/remarkjs/react-markdown)

## 🚀 Installazione e Avvio

Per eseguire questo progetto in locale, segui questi passaggi:

1.  **Clona il repository**
    ```bash
    git clone https://github.com/tuo-username/ricettaio.git
    cd ricettaio
    ```

2.  **Installa le dipendenze**
    ```bash
    npm install
    ```

3.  **Ottieni una API Key**
    - Vai su [Google AI Studio](https://aistudio.google.com/app/apikey) e crea una nuova chiave API gratuita per i modelli Gemini.

4.  **Avvia l'applicazione**
    ```bash
    npm start
    ```
    L'applicazione sarà disponibile nel tuo browser all'indirizzo `http://localhost:3000`.

## ⚙️ Utilizzo

Una volta avviata l'applicazione:

1.  Incolla la tua chiave API di Google AI nell'apposito campo in alto.
2.  Scrivi gli ingredienti che hai a disposizione nell'area di testo.
3.  Clicca su "Genera Ricetta" e attendi il risultato!

---

Questo progetto è stato sviluppato con l'assistenza di un modello linguistico di Google.