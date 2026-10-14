# n8n Google Drive PDF-Import — Statische GitHub Pages-Website

Kurz: Diese minimal-statische Website informiert über eine private n8n-Automatisierung, die PDF-Dateien aus einem freigegebenen Google-Drive-Ordner in eine lokal gehostete Paperless-ngx-Instanz importiert.

## Dateien
- index.html — Startseite
- privacy.html — Datenschutzerklärung
- style.css — Stylesheet

## Veröffentlichen mit GitHub Pages
1. Committe die Dateien in dein Repository (z.B. in den Default-Branch `main`).
2. Im Repository auf GitHub: Einstellungen → `Pages`.
3. Wähle als Quelle:
   - Für eine Projektseite: Branch `main` und Ordner `/ (root)` oder `/docs`.
   - Für eine Benutzer-/Organisationsseite: Repository muss `username.github.io` heißen; wähle Branch `main` und Ordner `/`.
4. Speichern — GitHub baut und veröffentlicht die statische Seite. Die URL wird dort angezeigt.
5. Optional: Aktiviere `Enforce HTTPS` in den Pages-Einstellungen, sobald das Zertifikat verfügbar ist.

## Custom Domain (optional)
- Für eine Subdomain (z.B. `www.example.com`): Lege einen CNAME-Eintrag an, der auf `USERNAME.github.io` zeigt. Zusätzlich kannst du eine Datei `CNAME` mit der Domain in das Repository-Root einfügen.
- Für eine Apex-Domain (z.B. `example.com`): Lege A-Records zu den GitHub-Pages-IP-Adressen an.

## Wichtige Hinweise
- Die Website enthält keine Formulare, keine Logins und keine Tracking-/Analyse-Skripte.
- Die tatsächliche Verarbeitung der Dateien erfolgt in deiner privaten Infrastruktur — prüfe dort die Sicherheitseinstellungen selbstständig.
- Verantwortlicher: Albert Oudehinken
- Kontakt: oudehinken53@gmail.com

## Typische DNS-Einträge für eigene Domain
- Apex-Domain (`example.com`):
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- Subdomain (`www.example.com`):
  - CNAME → `USERNAME.github.io`

## Hinweis
Diese Vorlage dient als einfache, statische Informationsseite. Vor der Veröffentlichung prüfe bitte, ob die Rechts- und Datenschutzangaben für deinen konkreten Fall ausreichen.
