# 🎵 CanzoniFy - Landing Page V2

Landing page completa per il test di personalità artistica di CanzoniFy.

## 📦 Contenuto

- `index.html` - Landing page principale con tutte le sezioni
- `privacy.html` - Privacy Policy completa
- `logo.png` - Logo CanzoniFy
- `README.md` - Questo file

## ✨ Caratteristiche

### Design
- ✅ Design vibrante con colori brand (#aa4df7 + #f0cb01)
- ✅ Animazioni eleganti e fluide
- ✅ 100% responsive (perfetto su mobile e desktop)
- ✅ Effetti particelle e animazioni scroll-triggered

### Sezioni Incluse
1. **Hero** - Copy emozionale con CTA
2. **Gallery** - Slider infinito con 32 personalità (immagini da Drive)
3. **Trust** - Sezione "Perché fidarsi" con disclaimer
4. **Come Funziona** - 3 step animati
5. **Benefits** - 4 card con vantaggi
6. **FAQ** - 7 domande con accordion animato
7. **Chi Siamo** - Storia di Ari & Rob
8. **Form** - Google Form embedded
9. **Footer** - Link, social, trust badges
10. **Privacy Policy** - Pagina separata completa

### Funzionalità
- ✅ Modal interattivi per le personalità
- ✅ FAQ accordion animato
- ✅ Smooth scroll
- ✅ Lazy loading immagini
- ✅ Meta tags per SEO e social share
- ✅ Favicon
- ✅ Performance ottimizzate

## 🚀 Deploy su GitHub Pages

### Metodo 1: Upload Web (PIÙ FACILE)

1. Vai su: https://github.com/canzonify/canzonifyTest
2. Clicca su **"Add file"** → **"Upload files"**
3. Trascina questi file:
   - `index.html`
   - `privacy.html`
   - `logo.png`
   - `README.md` (opzionale)
4. Scrivi messaggio: "Landing V2 completa"
5. Clicca **"Commit changes"**
6. Vai su **Settings** → **Pages**
7. Seleziona Branch: **main**, Folder: **/ (root)**
8. Clicca **Save**
9. Aspetta 2-3 minuti
10. Il sito sarà live su: `https://canzonify.github.io/canzonifyTest/`

### Metodo 2: Git Command Line

```bash
# Clona il repository
git clone https://github.com/canzonify/canzonifyTest.git
cd canzonifyTest

# Copia i nuovi file
cp index.html privacy.html logo.png README.md ./

# Commit e push
git add .
git commit -m "Landing V2 completa con 32 personalità"
git push origin main

# GitHub Pages si aggiornerà automaticamente in 2-3 minuti
```

## 📸 Immagini delle Personalità

Le immagini sono caricate direttamente da Google Drive usando link pubblici:
- Formato: `https://drive.google.com/uc?export=view&id=FILE_ID`
- **Importante**: La cartella Drive deve essere pubblica ("Chiunque con il link può visualizzare")

### Verifica Accesso Immagini
Se le immagini non si vedono:
1. Vai su: https://drive.google.com/drive/folders/1faV7dduKpXlno2W39yy-ooWOqFGXhbYx
2. Clicca destro sulla cartella → "Condividi"
3. Imposta: "Chiunque con il link - Visualizzatore"

## 🔧 Personalizzazione

### Colori
I colori sono definiti in `:root` nel CSS:
```css
--primary: #aa4df7;
--secondary: #f0cb01;
--white: #ffffff;
```

### Testi
Tutti i testi sono nel file `index.html` e facilmente modificabili.

### Form Google
Per cambiare il form, sostituisci l'URL nell'iframe:
```html
<iframe src="TUO_NUOVO_FORM_URL?embedded=true">
```

## 📱 Social Links

Link già configurati:
- Instagram: [@canzonify](https://www.instagram.com/canzonify/)
- TikTok: [@canzonify_ita](https://www.tiktok.com/@canzonify_ita)
- Facebook: [Canzonify](https://www.facebook.com/share/19kE7QpSnE/)
- Email: canzonify@gmail.com
- Sito: [canzonify.com](https://canzonify.com)

## 🧪 Test Locale

Per testare localmente prima del deploy:

1. Apri `index.html` nel browser (doppio click)
2. Oppure usa un server locale:
   ```bash
   # Python 3
   python3 -m http.server 8000
   # Poi vai su: http://localhost:8000
   ```

## 📊 Analytics (Opzionale)

Per aggiungere Google Analytics:
1. Ottieni il tuo ID tracking
2. Aggiungi prima di `</head>` in `index.html`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🐛 Troubleshooting

### Immagini non si caricano
- Verifica che la cartella Drive sia pubblica
- Controlla gli ID dei file nel codice
- Apri Console browser (F12) per vedere errori

### Form non appare
- Verifica URL del form Google
- Controlla che il form sia impostato per accettare risposte
- Prova ad aumentare `min-height` dell'iframe

### Animazioni non funzionano
- Assicurati che JavaScript sia abilitato
- Controlla Console browser per errori

## 📞 Supporto

Per problemi o domande:
- Email: canzonify@gmail.com
- GitHub Issues: https://github.com/canzonify/canzonifyTest/issues

## 📄 Licenza

© 2025 CanzoniFy - Tutti i diritti riservati

---

## 🎉 Next Steps

Dopo il deploy:
1. ✅ Testa il sito su vari dispositivi (mobile, tablet, desktop)
2. ✅ Verifica che tutte le immagini si carichino
3. ✅ Compila il form per testare il flusso completo
4. ✅ Condividi il link sui social!

**URL Finale:** `https://canzonify.github.io/canzonifyTest/`

---

Made with 💜 for Artists by CanzoniFy
