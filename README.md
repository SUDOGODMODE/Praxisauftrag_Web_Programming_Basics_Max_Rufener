# CV-Webseite Max Rufener

## Was ist das hier?

Das ist meine CV-Webseite die ich im Rahmen der Praxisarbeit an der HFTM erstellt habe.

## Aktueller Stand

Was bisher fertig ist:

- `index.html` mit meinem vollständigen Lebenslauf
- `style.css` als externes Stylesheet
- Responsive Layout funktioniert auf Mobile und Desktop
- Semantische HTML5-Tags verwendet
- Bild eingebunden
- `README.md` hinzugefügt

  
Was noch fehlt:

- Login / Passwortschutz
- Ein kleines JavaScript-Programm oder Gadget
- Online schalten via GitLab-Pages oder alwaysdata.com

---

## Dateistruktur

```
/
├── .DS_Store
├── index.html
├── style.css
├── foto.jpeg
└── README.md
```

---

## Wie ist das aufgebaut?

Das HTML verwendet semantische Tags wie `<main>`, `<header>`, `<section>`, `<time>`, `<figure>` usw. – also keine veralteten `<table>`-Layouts für das Design.

Das CSS ist komplett ausgelagert in `style.css` und wird so eingebunden:

```html
<link rel="stylesheet" href="style.css">
```

Für das responsive Layout habe ich Flexbox und einen Media Query verwendet:

```css
@media (max-width: 600px) {
    /* Mobile Anpassungen */
}
```

---

## Technologien

- HTML5
- CSS3
- Kein Framework, kein JavaScript bisher

---

## Autor & Abgabe

Max Aaron Rufener  
HFTM Grenchen, Dipl. Systemtechniker HF  
Abgabe: 29. Mai via Moodle
