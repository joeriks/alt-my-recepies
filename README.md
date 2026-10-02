# alt-my-recepies

Mina appar, samlingar och recept för [alt](https://github.com/joeriks/alt).
Appen hämtar härifrån. Data ligger aldrig här, den ligger i alt-my-data.

Tekniska namn och etiketter skrivs på engelska. `lang/sv.yaml` ersätter etiketterna
när telefonen är inställd på svenska.

- `apps/<app>/app.yaml` beskriver en app.
- `apps/<app>/<name>.collection.yaml` beskriver en samling: fält, roll och kryptering.
- `types/<name>.type.yaml` är en delad struktur som flera samlingar kan använda med `type: <name>`.
- `apps/<app>/<name>.recipe` är ett recept: YAML-huvud och JavaScript.
- `lang/<språk>.yaml` innehåller etiketter på andra språk.
