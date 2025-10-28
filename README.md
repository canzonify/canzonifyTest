# 🎵 CanzoniFy - Landing Page

Landing page per il test di personalità artistica CanzoniFy.

## 📁 File inclusi

- `index.html` - Landing page completa
- `logo.png` - Logo CanzoniFy (da aggiungere)
- `README.md` - Questo file

## 🚀 Come pubblicare su GitHub Pages (GRATIS)

### Passo 1: Crea un repository GitHub

1. Vai su [GitHub](https://github.com)
2. Clicca su "New repository" (verde in alto a destra)
3. Nome repository: `canzonify-landing` (o quello che preferisci)
4. Seleziona: **Public**
5. NON selezionare "Add a README"
6. Clicca "Create repository"

### Passo 2: Carica i file

**Opzione A - Dal sito GitHub (più facile):**

1. Nel repository appena creato, clicca "uploading an existing file"
2. Trascina questi file:
   - `index.html`
   - `logo.png` (usa l'immagine su sfondo bianco: Canzonify-8.png)
3. Scrivi un messaggio tipo: "Initial commit"
4. Clicca "Commit changes"

**Opzione B - Da terminale (se sai usare git):**

```bash
# Nella cartella con i file
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TUO-USERNAME/canzonify-landing.git
git push -u origin main
```

### Passo 3: Attiva GitHub Pages

1. Nel repository, clicca su "Settings"
2. Nel menu laterale, clicca "Pages"
3. Sotto "Source", seleziona:
   - Branch: `main`
   - Folder: `/ (root)`
4. Clicca "Save"
5. Aspetta 1-2 minuti
6. Ricarica la pagina Settings → Pages
7. Vedrai il link del tuo sito: `https://tuo-username.github.io/canzonify-landing/`

## 🎨 Personalizzazioni

### Cambiare il logo

Rinomina il tuo logo in `logo.png` e sostituiscilo.

### Modificare i testi

Apri `index.html` e modifica le sezioni:
- **Hero title:** Riga ~93
- **Tagline:** Riga ~96
- **CTA:** Riga ~101
- **Benefits:** Righe ~106-118

### Cambiare i colori

Nel tag `<style>` (righe 15-200):
- Colore primario viola: `#aa4df7`
- Colore giallo: `#f0cb01`
- Cerca e sostituisci se vuoi cambiarli

## 📱 Test locale

Per testare prima di pubblicare:

1. Apri `index.html` direttamente nel browser
2. Oppure usa un server locale:
   ```bash
   # Con Python
   python -m http.server 8000
   
   # Poi apri: http://localhost:8000
   ```

## ⚙️ Problemi comuni

### Il form non si vede?

- Controlla che l'URL del form sia corretto
- Il form deve essere in modalità "Accetta risposte"
- Prova a riaprire il link del form in una finestra privata

### Il logo non appare?

- Assicurati che il file si chiami esattamente `logo.png`
- Deve essere nella stessa cartella di `index.html`

### Altezza del form troppo bassa?

Nell'`index.html`, riga ~162, modifica:
```css
min-height: 2000px; /* Aumenta o diminuisci questo valore */
```

## 🎯 Prossimi passi

Una volta pubblicato:

1. Testa su mobile e desktop
2. Condividi il link per feedback
3. Monitora le risposte nel Google Form

## 🆘 Supporto

Problemi? Domande? 
- Controlla che tutti i file siano nella stessa cartella
- Verifica che GitHub Pages sia attivato
- Aspetta 2-3 minuti dopo ogni modifica

---

✨ **Fatto con passione per CanzoniFy**
