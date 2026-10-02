# alt-my-recepies

Mina appar, samlingar och recept för [alt](https://github.com/joeriks/alt).
Appen hämtar härifrån. Data ligger aldrig här, den ligger i alt-my-data.

- `apps/<app>/app.yaml` beskriver en app.
- `apps/<app>/<namn>.collection.yaml` beskriver en samling: fält, roll och kryptering.
- `types/<namn>.type.yaml` är en delad struktur som flera samlingar kan använda med `type: <namn>`.
- `apps/<app>/<namn>.recipe` är ett recept: YAML-huvud och JavaScript.
