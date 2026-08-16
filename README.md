# .github

Das Schaufenster der Organisation, sonst nichts. Hier liegt kein Code.

- **[profile/README.md](profile/README.md)** — der Text, den GitHub auf
  [github.com/rheingeladen](https://github.com/rheingeladen) über der
  Repository-Liste einblendet. Das ist die einzige Seite der Organisation, die
  jeder sieht; die Arbeit selbst liegt in privaten Repositories.
- **[assets/org-avatar.svg](assets/org-avatar.svg)** — die Quelle des
  Organisationsbildes. GitHub nimmt nur Rasterbilder entgegen, das Bild wird
  also aus dieser Datei erzeugt und in der Weboberfläche hochgeladen (Settings →
  Profile → Upload new picture). Die Datei liegt hier, damit das Zeichen bei
  der nächsten Änderung nicht neu gezeichnet werden muss:

  ```bash
  rsvg-convert -w 640 -h 640 assets/org-avatar.svg -o org-avatar.png
  ```

Dieses Repository ist öffentlich — das muss es sein, sonst zeigt GitHub den
Profiltext nicht an. Alles, was nicht in ein Schaufenster gehört, gehört
deshalb nicht hierher.
