# Nowhere Pictures - Website Vetrina

Sito web minimalista per Nowhere Pictures con video fullscreen e pagina About.

## 📁 File del progetto

- `index.html` - Homepage con video fullscreen
- `about.html` - Pagina About con testi
- `styles.css` - Stili condivisi

## 📦 File che devi preparare

Prima di caricare il sito online, devi aggiungere questi file nella stessa cartella:

### 1. Font Centra No2
Rinomina i tuoi file font esattamente così:
- `CentraNo2-Book.woff2` e `CentraNo2-Book.woff`
- `CentraNo2-Medium.woff2` e `CentraNo2-Medium.woff`
- `CentraNo2-Bold.woff2` e `CentraNo2-Bold.woff`

### 2. Video
- `video.mp4` - Il tuo video per la homepage

### 3. Immagine Fallback
- `fallback-image.jpg` - Immagine che appare se il video non si carica

### 4. Logo
- `logo.png` - Il logo che appare al centro del menu (formato PNG con sfondo trasparente consigliato)

### 5. Loghi Footer (solo per pagina About)
- `logo-nowhere-small.png` - Logo Nowhere Pictures piccolo per il footer
- `logo-sponsor.png` - Logo dello sponsor per il footer

## ✏️ Personalizzazioni da fare

### 1. Link Social Media
Apri sia `index.html` che `about.html` e sostituisci:
- `YOUR_INSTAGRAM` con il tuo nome utente Instagram
- `YOUR_LINKEDIN` con il tuo nome LinkedIn/company

Esempio:
```html
<!-- Da questo -->
<a href="https://instagram.com/YOUR_INSTAGRAM" target="_blank">

<!-- A questo -->
<a href="https://instagram.com/nowherepictures" target="_blank">
```

### 2. Testi About
Apri `about.html` e sostituisci il testo tra i tag `<!-- INSERISCI QUI I TUOI TESTI -->` e `<!-- FINE TESTI DA SOSTITUIRE -->` con i tuoi testi.

## 🚀 Come caricare il sito online (Opzioni gratuite)

### Opzione 1: Netlify (Consigliata - Più semplice)

1. Vai su [www.netlify.com](https://www.netlify.com)
2. Registrati gratuitamente
3. Trascina l'intera cartella del sito nell'area "Drag and drop"
4. Il sito sarà online in pochi secondi!
5. Riceverai un indirizzo tipo: `nome-casuale.netlify.app`
6. Puoi collegare il tuo dominio personalizzato (se ne hai uno)

### Opzione 2: Vercel

1. Vai su [vercel.com](https://vercel.com)
2. Registrati con GitHub, GitLab o email
3. Clicca "Add New Project"
4. Carica i file del sito
5. Il sito sarà online automaticamente

### Opzione 3: GitHub Pages

1. Crea un account su [github.com](https://github.com)
2. Crea un nuovo repository chiamato `username.github.io` (sostituisci username con il tuo)
3. Carica tutti i file
4. Vai su Settings > Pages
5. Seleziona la branch main e salva
6. Il sito sarà disponibile su `username.github.io`

## 📱 Il sito è responsive

Il sito si adatta automaticamente a:
- Desktop
- Tablet
- Mobile

## 🎨 Caratteristiche

- Design minimalista bianco/nero
- Video fullscreen con autoplay e loop
- Fallback automatico a immagine se il video non carica
- Menu fisso con logo centrale
- Icone social Instagram e LinkedIn
- Footer solo nella pagina About
- Font personalizzato Centra No2
- Completamente responsive

## 🔧 Modifiche future

Se vuoi modificare i testi o i colori in futuro:
- **Testi**: apri i file `.html` con un editor di testo qualsiasi
- **Colori**: apri `styles.css` e modifica i valori dei colori (#ffffff = bianco, #000000 = nero)
- **Dimensioni font**: sempre in `styles.css`

## ⚠️ Checklist finale prima di caricare online

- [ ] Ho aggiunto tutti i file font (6 file .woff e .woff2)
- [ ] Ho aggiunto il video.mp4
- [ ] Ho aggiunto la fallback-image.jpg
- [ ] Ho aggiunto il logo.png (menu)
- [ ] Ho aggiunto logo-nowhere-small.png (footer)
- [ ] Ho aggiunto logo-sponsor.png (footer)
- [ ] Ho sostituito i link Instagram e LinkedIn
- [ ] Ho inserito i miei testi nella pagina About
- [ ] Tutti i file sono nella stessa cartella

## 📧 Contatti

Nowhere Pictures
via Giuseppe Fanelli 289, 70125 Bari
VAT IT08735920723
