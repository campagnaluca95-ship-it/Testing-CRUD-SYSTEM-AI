# Testing CRUD System AI

Un sistema CRUD (Create, Read, Update, Delete) completo per la gestione di utenti, sviluppato come progetto di testing e prototipazione con supporto AI.

## 📋 Descrizione

Questo progetto implementa un'applicazione web full-stack per la gestione degli utenti con interfaccia intuitiva e backend Node.js. È progettato come piattaforma di testing e sperimentazione con intelligenza artificiale.

## 🚀 Funzionalità

- ✅ **Create**: Aggiungi nuovi utenti al sistema
- ✅ **Read**: Visualizza tutti gli utenti registrati
- ✅ **Update**: Modifica i dati degli utenti esistenti
- ✅ **Delete**: Rimuovi utenti dal database

## 🛠️ Tecnologie Utilizzate

- **Frontend**: 
  - HTML5
  - CSS3
  - JavaScript (vanilla)

- **Backend**:
  - Node.js
  - SQLite3
  - Express.js (implicito dalla struttura server)

- **Database**:
  - SQLite (file-based: `database.db`)

## 📁 Struttura del Progetto

```
Testing-CRUD-SYSTEM-AI/
├── index.html          # Interfaccia web principale
├── style.css           # Stili CSS per la UI
├── server.js           # Server Node.js
├── package.json        # Dipendenze e configurazione progetto
├── database.db         # Database SQLite (generato al primo avvio)
└── README.md           # Questo file
```

## 🔧 Installazione

1. **Clone il repository**
   ```bash
   git clone https://github.com/campagnaluca95-ship-it/Testing-CRUD-SYSTEM-AI.git
   cd Testing-CRUD-SYSTEM-AI
   ```

2. **Installa le dipendenze**
   ```bash
   npm install
   ```

3. **Avvia il server**
   ```bash
   npm start
   # oppure
   node server.js
   ```

4. **Accedi all'applicazione**
   - Apri il browser e vai su `http://localhost:3000` (o la porta configurata)

## 📊 Struttura del Database

La tabella `users` contiene i seguenti campi:

- `id` (INTEGER PRIMARY KEY AUTOINCREMENT): ID univoco
- `nome` (TEXT NOT NULL): Nome dell'utente
- `email` (TEXT NOT NULL): Email dell'utente

## 💻 Utilizzo

### Aggiungere un Utente
1. Compila il modulo con nome e email
2. Clicca su "Aggiungi"

### Visualizzare Utenti
- La lista viene aggiornata automaticamente dopo ogni operazione

### Modificare un Utente
1. Seleziona l'utente dalla lista
2. Modifica i dati nel modulo
3. Clicca su "Aggiorna"

### Eliminare un Utente
1. Clicca sul pulsante "Elimina" accanto all'utente desiderato
2. Conferma l'eliminazione

## 📝 API Endpoints (Backend)

Tipicamente esposti dal server:
- `GET /api/users` - Ottieni tutti gli utenti
- `POST /api/users` - Crea un nuovo utente
- `PUT /api/users/:id` - Aggiorna un utente
- `DELETE /api/users/:id` - Elimina un utente

## 🧪 Testing

Questo progetto è progettato come piattaforma di testing. Per eseguire test:

```bash
npm test
```

## 🤖 AI Integration

Il progetto è stato sviluppato con supporto e testing di sistemi AI per validare:
- Generazione automatica di CRUD
- Testing dell'interfaccia utente
- Prototipazione assistita

## ⚙️ Requisiti di Sistema

- **Node.js**: v14.0 o superiore
- **npm**: v6.0 o superiore
- **Browser**: Moderno (Chrome, Firefox, Safari, Edge)

## 📦 Dipendenze Principali

- `sqlite3`: Driver SQLite per Node.js
- `express`: Framework web per Node.js (opzionale, a seconda della configurazione)

## 🐛 Risoluzione dei Problemi

### Il database non si crea
- Verifica che la cartella del progetto abbia permessi di scrittura
- Assicurati che SQLite3 sia installato correttamente

### La connessione al server fallisce
- Verifica che la porta sia disponibile
- Controlla i log della console per eventuali errori

### Gli utenti non vengono salvati
- Verifica la connessione al database
- Controlla che il file `database.db` esista nella directory root

## 📄 Licenza

Questo progetto è fornito come è, senza licenza specifica.

## 👤 Autore

- **campagnaluca95-ship-it** - [GitHub Profile](https://github.com/campagnaluca95-ship-it)

## 🤝 Contributi

I contributi sono benvenuti! Se vuoi:
1. Fai un fork del progetto
2. Crea un branch per la tua feature (`git checkout -b feature/AmazingFeature`)
3. Commit le tue modifiche (`git commit -m 'Add some AmazingFeature'`)
4. Push nel branch (`git push origin feature/AmazingFeature`)
5. Apri una Pull Request

## 📞 Support

Per domande, problemi o suggerimenti, apri un issue nel repository.

---

**Nota**: Questo è un progetto di testing e prototipazione. Per uso in produzione, considera di aggiungere validazione input, autenticazione, e ulteriori misure di sicurezza.
