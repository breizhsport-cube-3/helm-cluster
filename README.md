# Comment mettre en place le cluster sur ArgoCD

## Créer une application
- Configurer le nom.
- Ajouter en source repositories *.
- Ajouter en destination le server par défaut.
- Dans cluster resource allow list :
  - Kind : *
  - Group : *
- Dans cluster allow list :
  - Kind : *
  - Group : *
## Créer une application
- Dans le projet name, remettre le nom de l'application créer précédemment.
- Renseigner l'url du repository github.
- Mettre ./ en path.
- Mettre l'url du cluster par défaut.
- Définir un namespace et coché auto-create namespace.