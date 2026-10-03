ZAMAZA BRAND-IMPERSONATION-SIMULATION

index.html = Startseite; öffnet real.html und fake.html in zwei Tabs
real.html  = bereitgestellte Zamaza Shop.html
fake.html  = bereitgestellte Zamaza Shop Pro.html

LOKAL TESTEN:
python -m http.server 8000
Dann http://localhost:8000/

ONLINE:
Die vier Dateien können auf einem statischen Hosting-Dienst wie GitHub Pages,
Netlify oder Cloudflare Pages veröffentlicht werden. Keine Serverlogik nötig.
Bei GitHub Pages: Repository erstellen -> Dateien hochladen -> Settings -> Pages
-> Deploy from branch -> main/root. Danach die erzeugte Pages-Adresse teilen.

Hinweis: Browser können den zweiten Tab als Popup blockieren. Popups für die
Hosting-Domain erlauben. Beide window.open-Aufrufe werden durch denselben Button-Klick ausgelöst.

Für die Unterrichtssimulation keine echten Zahlungs-, Konto- oder Passwortdaten eingeben.
