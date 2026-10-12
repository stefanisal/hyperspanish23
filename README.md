# HyperSpanish PWA v1.1

Εφαρμογή εκμάθησης Ισπανικών (2199 προτάσεις, CEFR A1–C1).

## Εγκατάσταση / χρήση

### Τοπικά (γρήγορα)
Χρειάζεται τοπικός server (λόγω Service Worker):

```bash
# Python
cd HyperSpanish_PWA
python3 -m http.server 8080

# ή Node
npx serve .
```

Άνοιξε http://localhost:8080 στο Chrome/Edge/Safari.
Μενού → «Εγκατάσταση εφαρμογής» / Install.

### Σε hosting
Ανέβασε ΟΛΟ τον φάκελο σε HTTPS hosting (Netlify, Vercel, GitHub Pages, Cloudflare Pages κ.λπ.).
Το PWA λειτουργεί μόνο σε HTTPS (ή localhost).

### iOS (Safari)
Share → Προσθήκη στην οθόνη Αφετηρίας.

### Android (Chrome)
Εμφανίζεται banner εγκατάστασης ή μενού → Εγκατάσταση εφαρμογής.

## Περιεχόμενα
- index.html – η εφαρμογή
- manifest.webmanifest – metadata PWA
- sw.js – offline cache
- icons/ – εικονίδια

Τα δεδομένα (αγαπημένα, SRS, μαθημένες) μένουν στο localStorage της συσκευής.
