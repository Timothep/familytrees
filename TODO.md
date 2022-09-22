1. Install Kingraph
> npm install -g rstacruz/kingraph

2. Install GraphViz
> brew install graphviz

3. Generate DOT and SVG in one go
> kingraph simon.yml --format=dot > simon.dot && dot -Tsvg simon.dot > simon.svg
> kingraph bourguignon.yml -F dot > bourguignon.dot && dot -Tsvg bourguignon.dot > bourguignon.svg


[x] Ajouter les dates de naissance dans le fichier Excel
[x] Générer les dates de naissance avec Flow dans le YAML
[x] Importer la généalogie Simon
[ ] Fix the full generation problem
  [ ] Attempt a npm update
  [ ] Search the web for more ideas
[ ] Héberger le SVG avec un mot de passe qqpart

[ ] Mechanisme pour soumettre les naissances
[ ] Photos?