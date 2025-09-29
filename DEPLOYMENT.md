# 🚀 Deployment Anleitung

## Option 1: Netlify (Empfohlen - Kostenlos)

### Schritt 1: Website-Dateien vorbereiten
```bash
# Die Website ist bereits im /website Ordner fertig
cd website/
```

### Schritt 2: Netlify Deployment
1. Gehe zu [netlify.com](https://netlify.com)
2. Klicke auf "Deploy to Netlify"
3. Drag & Drop den gesamten `website` Ordner auf die Netlify-Seite
4. Deine Website ist sofort live!

**Oder mit Git:**
1. Erstelle ein neues GitHub Repository
2. Lade den website-Ordner hoch
3. Verbinde das Repository mit Netlify
4. Automatisches Deployment bei jedem Update

### Schritt 3: Custom Domain (Optional)
- Kostenlose `.netlify.app` Subdomain ist bereits enthalten
- Eigene Domain kann für ~10€/Jahr hinzugefügt werden

---

## Option 2: Vercel (Ebenfalls kostenlos)

### Deployment mit Vercel:
```bash
# Vercel CLI installieren
npm install -g vercel

# In website-Ordner navigieren
cd website/

# Deployment
vercel --prod
```

---

## Option 3: GitHub Pages (Kostenlos)

### Setup:
1. GitHub Repository erstellen
2. Website-Dateien hochladen
3. In Repository Settings → Pages
4. Source: "Deploy from a branch" → main branch
5. Website ist verfügbar unter: `username.github.io/repository-name`

---

## 📱 Nach dem Deployment

### 1. URL testen
- Prüfe alle Links und Funktionen
- Teste auf verschiedenen Geräten
- Validiere responsive Design

### 2. SEO optimieren
- Google Search Console hinzufügen
- Sitemap erstellen (falls erforderlich)
- Meta-Tags validieren

### 3. Analytics (Optional)
```html
<!-- Google Analytics Code in <head> einfügen -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

---

## 🔧 Updates

### Netlify mit Git:
```bash
# Änderungen machen
# Dann:
git add .
git commit -m "Website update"
git push
# Netlify deployed automatisch!
```

### Netlify ohne Git:
- Einfach den aktualisierten Ordner erneut hochladen

---

## ✅ Checkliste vor dem Launch

- [ ] Alle Links funktionieren
- [ ] Mobile Ansicht getestet
- [ ] Ladezeiten optimiert
- [ ] SEO Meta-Tags gesetzt
- [ ] Kontaktdaten aktualisiert
- [ ] App Store Links hinzugefügt (sobald verfügbar)
- [ ] SSL-Zertifikat aktiv (automatisch bei Netlify/Vercel)
- [ ] Custom Domain konfiguriert (optional)

---

## 🎯 Kosten-Übersicht

**Netlify Free Tier:**
- ✅ Unbegrenzte statische Websites
- ✅ 300 Build-Minuten/Monat
- ✅ 100GB Bandwidth/Monat
- ✅ SSL-Zertifikat inklusive
- ✅ `.netlify.app` Subdomain

**Custom Domain (Optional):**
- ~10-15€/Jahr für .com/.de Domain
- DNS-Setup über Netlify oder Domain-Provider

**Total: 0€ bis 15€/Jahr** 🎉