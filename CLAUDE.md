# forma-mcp-au

Arbeitskopie des APS-MCP-Workshops von Autodesk University 2026. Fremder Code,
getrennt vom führenden Repo `dev\mcp\Forma-MCP` gehalten, damit Workshop-Code
und eigene Änderungen daran nicht dort landen.

## Herkunft

Gemessen am 01.11.2026 mit `git remote -v` und `git log`:

- Fork von `autodesk-platform-services/au2026-mcp-workshop-beginner`, als
  Remote `upstream` eingetragen. `package.json` heißt
  `au2026-mcp-workshop-advanced`.
- Eigene private Kopie: `origin` ist `mk92at/forma-mcp-au` auf GitHub.
- 44 Commits auf `main`, der jüngste vom 11.09.2026 aus dem Upstream. Eigene
  Workshop-Änderungen liegen uncommittet im Arbeitsstand (`aps.js`, `mcp.js`,
  `index.js`, `proxy.js`, `viewer.html`).
- Lizenz: Im Upstream-Stand liegt keine LICENSE-Datei. Vor einer Weitergabe
  klären.

## Arbeiten hier

- Einrichtung, Callback-URL, Start und bekannte Fallen: Skill `aps-workshop`.
- Keine Kontobindung, Konto je Chat (Runde 08). Kürzel FORMA-AU in
  `dev\autodesk-setup\projects.md`.
- Zugangsdaten (APS Client-ID und Secret) gehören nach Bitwarden, nicht in die
  `.env` (Skill `bitwarden`).
- Eigene Werkzeuge für Forma entstehen in `Forma-MCP`, nicht hier.
