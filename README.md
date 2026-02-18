# 🎀 Hello Kitty Adventure - Pink Match-3 Game 🎀

Un adorabile gioco match-3 con i personaggi Hello Kitty Sanrio! Gioca 20 livelli per ogni personaggio con difficoltà progressiva, combo e bombe speciali.

## 🎮 Features

✨ **6 Personaggi Giocabili:**
- Hello Kitty 🎀 (Sbloccato)
- My Melody 🐰
- Badtz-Maru 🐧
- Keroppi 🐸
- Gudetama 🥚
- Pompompurin 🐕

🎯 **Gameplay:**
- 20 livelli per personaggio
- Difficoltà progressiva
- Combo system con moltiplicatori
- Bombe speciali (4+ abbinamenti = 💣)
- Target score per vincere ogni livello
- Move-based system

🎨 **Grafica:**
- Tema rosa pastello
- Animazioni smooth
- Interfaccia user-friendly
- Responsive design (mobile-ready)

💾 **Save System:**
- Progresso automatico con localStorage
- Sblocco personaggi completando i livelli
- Nessun backend necessario

## 📱 Come Giocare Online (GitHub Pages)

### Opzione 1: Setup Automatico (Consigliato)

1. **Vai su GitHub.com** e accedi al tuo account (crea uno se non ce l'hai)

2. **Crea un nuovo repository:**
   - Click su `+` (top right) → `New repository`
   - Nome: `hello-kitty-adventure`
   - Descrizione: `Hello Kitty Match-3 Game`
   - Scegli "Public"
   - Click `Create repository`

3. **Carica i file:**
   - Nella pagina del repository, click `uploading an existing file`
   - Trascina il file `Ultimate.html` dalla cartella `hello-kitty-github-pages` sul browser
   - Click `Commit changes`

4. **Attiva GitHub Pages:**
   - Vai su `Settings` (tab nel repo)
   - Scroll a `Pages` (left sidebar)
   - Source: seleziona `main`
   - Click `Save`

5. **Accedi al gioco:**
   - Il sito sarà disponibile a: `https://[tuo-username].github.io/hello-kitty-adventure`
   - Apri il link dal cellulare per giocare!

### Opzione 2: Setup via Git (Per Developer)

```bash
# 1. Apri terminal nella cartella hello-kitty-github-pages
cd c:\Users\Acer\Desktop\web\hello-kitty-github-pages

# 2. Inizializza git
git init

# 3. Aggiungi il file
git add Ultimate.html

# 4. Commit
git commit -m "Initial Hello Kitty Game"

# 5. Aggiungi remote (sostituisci USERNAME e REPO)
git remote add origin https://github.com/USERNAME/hello-kitty-adventure.git

# 6. Push
git push -u origin main

# 7. Attiva Pages dalle impostazioni di GitHub
```

## 🎮 Come Giocare

1. **Seleziona personaggio** - Scegli Hello Kitty per iniziare
2. **Abbina 3+ tile** - Clicca due tile adiacenti per scambiarle
3. **Raccogli combo** - Moltiplica il punteggio con abbinamenti consecutivi
4. **Usa le bombe** - 4+ abbinamenti creano bombe 💣 (esplodono 3x3)
5. **Raggiungi il target** - Accumula punti sufficienti prima di finire le mosse
6. **Sblocca personaggi** - Completa tutti i livelli di un personaggio per sbloccare il prossimo

## 💾 Salvataggio

Il tuo progresso è **salvato automaticamente** sul browser:
- Livelli completati per ogni personaggio
- Personaggi sbloccati
- Continua dove hai lasciato!

**Nota:** Dati salvati localmente - funzionano su qualsiasi dispositivo ma non sincronizzano tra browser diversi.

## 🛠️ Richieste Tecniche

- **Browser moderno** (Chrome, Firefox, Safari, Edge)
- **JavaScript abilitato**
- **LocalStorage** (sempre abilitato per impostazione predefinita)
- **Offline-ready** - Funziona senza internet dopo il primo caricamento!

## 📁 File Structure

```
hello-kitty-github-pages/
├── Ultimate.html      # Gioco completo (HTML5 + CSS3 + JS)
├── README.md          # Questo file
└── .gitignore         # Git config (optional)
```

## 🎨 Personalizzazione

Puoi modificare `Ultimate.html`:
- Colori: Cerca `#ff69b4` (pink), `#ff1493` (deep pink)
- Tile emoji: Modifica array `TILES`
- Difficoltà: Cambio formula in `playLevel()`
- Livelli: Modifica `levels: 20` in `CHARACTERS_DATA`

## 🐛 Troubleshooting

**Il gioco non carica?**
- Verifica che `Ultimate.html` sia nella root del repository
- Attendi 1-2 minuti per GitHub Pages di aggiornarsi

**Progresso non salvato?**
- LocalStorage richiede HTTPS (automatico su GitHub Pages)
- Controlla browser console (F12 → Console)

**Link non funziona?**
- Assicurati repository sia `Public`
- Verifica username nella URL

## 💝 Credits

Creato con amore per Sonia 💕  
Personaggi © Sanrio

---

**Divertiti a giocare! 🎮✨**
