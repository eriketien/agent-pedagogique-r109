# Agent pédagogique – R1.09 Électronique (prototype)

Prototype d'application mobile de suivi individualisé en électronique (BUT GEII, S1, travaux dirigés).
Contenu : chapitre 1 (conventions, loi d'Ohm) et chapitre 2 (résistances équivalentes, lois des nœuds et des mailles, diviseur de tension, superposition, Millman), avec correction automatique, remédiations ciblées et déblocage progressif.

Le prototype tient en un seul fichier, `index.html`. Il fonctionne sans serveur : aucune donnée n'est envoyée, la progression est enregistrée dans le navigateur de chaque utilisateur.

## Mise en ligne (GitHub Pages)
1. Créer un dépôt (par exemple `agent-pedagogique-r109`) dans l'espace GitHub de l'université.
2. Y déposer `index.html` et ce `README.md` (bouton « Add file » → « Upload files »), puis « Commit changes ».
3. Dans « Settings » → « Pages » : « Source : Deploy from a branch », branche `main`, dossier `/ (root)`, puis « Save ».
4. Au bout d'une ou deux minutes, l'adresse du site s'affiche en haut de la page « Pages ». C'est ce lien à envoyer aux évaluateurs.

Si l'instance GitHub de l'université le permet, régler la visibilité de la page sur « Private » pour la réserver aux membres de l'organisation.

## Guide pour les évaluateurs
Temps conseillé : 30 à 45 minutes, de préférence sur téléphone.

1. **Parcours étudiant** : ouvrir le lien et commencer par « Conventions C1.1–C1.2 ». Les étapes suivantes se débloquent au fur et à mesure (≥ 80 % de réussite du premier coup aux tests).
2. **Accès direct** : en bas de page, activer « Mode enseignant » pour ouvrir toutes les étapes sans les valider.
3. **Remédiations** : en mode enseignant, le bouton « Remédiations et signalements » permet de lancer chacune des remédiations (questions courtes → exemple guidé → alerte enseignant). Pour les voir se déclencher naturellement, faire volontairement la même erreur sur deux exercices.
4. **Réinitialiser** : en mode enseignant, « Réinitialiser la progression » (deux clics).

Points sur lesquels votre avis est attendu :
- justesse scientifique des énoncés, des corrections et des indices ;
- progressivité des niveaux (★ à ★★★★) et pertinence des tests de validation ;
- utilité des remédiations et de l'exemple guidé ;
- ergonomie sur téléphone (saisie des valeurs et préfixes, schémas, choix par touché) ;
- ce qui manque ou ce qui serait à retirer.

## Limites connues du prototype
- La progression reste sur l'appareil utilisé : il n'y a pas encore de compte, de serveur ni de tableau de bord enseignant.
- Les indices sont écrits à l'avance ; dans l'application finale, l'agent les adaptera à l'erreur de l'étudiant.
- Les chapitres 0 (diagnostic) et 4 à 7 ne sont pas encore construits.
