#poznamky
Toto jsou krátké poznámky k projektu. Zde si zaznamenávám, co jsem dělal/a během cvičení. Poznámky obsahují kroky pro vytvoření PR a release.
# 1. commit - přidej nadpis
echo "# Poznámky" > notes.md
git add notes.md
git commit -m "docs: přidej nadpis do notes.md"

# 2. commit - doplň poznámky
echo "Toto jsou krátké poznámky k projektu..." >> notes.md
git add notes.md
git commit -m "docs: doplň poznámky do notes.md"

# push větve na GitHub
git push -u origin feature/notes
