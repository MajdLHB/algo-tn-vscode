# Attribution

This project ("Algorithme TN — Exécuteur & Tableaux",
`MajdLHB.algorithme-tn-runner`) is a fork of:

- **algorithme-tn** — https://github.com/romoez/algo-tn-vscode
  by **les-profs-d-info** (Communauté Tunisienne des Enseignants d'Informatique)
  Licensed under the GNU General Public License v3.0.

The original extension provides the `.algo` language definition, TextMate
syntax highlighting, and code snippets, all retained here unchanged.

## Modifications in this fork (Majd Lahbib)

- Execution of `.algo` files by transpiling to Python (`tools/algotn.py`).
- A translate-only tool (`tools/traduire.py`) that emits Python without running it.
- VS Code commands: Run (▶ / F5 / Ctrl+F5), Translate to Python, Table editor.
- A declaration-table (TDO/TDOG/TDOL) editor and type diagnostics.

This fork remains licensed under the **GNU GPL-3.0**, the same license as the
original work. See the LICENSE file for the full text.
