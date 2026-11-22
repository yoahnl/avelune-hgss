# HGSS pour Avelune Studio

Ce dépôt contient le projet éditable de la reconstruction solo de Pokémon HeartGold dans Avelune. Les cartes, dialogues et ressources sont dans `jeu/`, avec le catalogue de travail et le profil d’export.

## Ouvrir le projet

1. Installer [Avelune Studio 0.3.39](https://github.com/yoahnl/avelune/releases/tag/avelune-studio-v0.3.39) ou une version compatible.
2. Cloner le dépôt avec Git.

   ```sh
   git clone https://github.com/yoahnl/avelune-hgss.git
   ```

3. Depuis l’accueil de Studio, cliquer sur **Ouvrir un autre projet** et choisir le dossier **`avelune-hgss/jeu`**, celui qui contient `project.json`. La première ouverture prépare les index locaux du catalogue et peut prendre plusieurs minutes.

Pour partager une modification, enregistrer dans Studio puis versionner ensemble les fichiers modifiés dans `jeu/`, y compris les nouveaux objets de `catalog/objects/` et le pointeur `catalog/HEAD.json`. Les contenus du catalogue sont identifiés par l’empreinte de leurs octets.

Les versions jouables pour Avelune Player sont disponibles dans les [livraisons HeartGold](https://github.com/yoahnl/heartgold-avelune-demo/releases).
