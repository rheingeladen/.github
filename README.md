# .github

Das Schaufenster der Organisation, sonst nichts. Hier liegt kein Code.

- **[profile/README.md](profile/README.md)** — der Text, den GitHub auf
  [github.com/rheingeladen](https://github.com/rheingeladen) über der
  Repository-Liste einblendet. Das ist die einzige Seite der Organisation, die
  jeder sieht; die Arbeit selbst liegt in privaten Repositories.
- **[assets/org-avatar.png](assets/org-avatar.png)** — das Organisationsbild,
  640 × 640, wie es in Settings → Profile → Upload new picture hochgeladen
  wird. Randlos: GitHub maskiert selbst, ein eigener Eckenradius darunter gäbe
  helle Zwickel auf dunklem Grund.

Das Zeichen selbst wird hier nicht gepflegt. Es steht als
`apps/web/src/app/icon.svg` im Hauptrepository — dieselbe Bildmarke, die auch
im Browsertab sitzt. Nach einer Änderung dort wird die Datei hier neu erzeugt,
ohne den Eckenradius des Favicons:

```bash
rsvg-convert -w 640 -h 640 icon.svg -o org-avatar.png   # rx="8" vorher entfernen
```

Dieses Repository ist öffentlich — das muss es sein, sonst zeigt GitHub den
Profiltext nicht an. Alles, was nicht in ein Schaufenster gehört, gehört
deshalb nicht hierher.
