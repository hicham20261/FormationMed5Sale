# FormationMed5Sale

Application web simple (HTML, CSS, JS) pour la gestion des retards des etudiants.

## Fonctionnalites

- Fiche etudiant: ajout avec champs `Nom` et `Prenom`.
- Interface de saisie des retards en minutes.
- Regle automatique: `1 minute de retard = 1 Dirham`.
- Tableau de bord:
	- total etudiants,
	- total minutes de retard,
	- total montant global en DH,
	- montant final par etudiant.
- Historique des retards enregistre.

## Stockage local

- `localStorage`: base de donnees locale (etudiants + retards).
- `sessionStorage`: etat temporaire de session (etudiant selectionne + brouillon de minutes).

## Lancer l'application

1. Ouvrir `index.html` dans un navigateur.
2. Ajouter les etudiants via la fiche.
3. Saisir les retards (minutes) depuis l'interface de gestion.
4. Consulter le tableau de bord pour voir le montant final a payer par chaque etudiant.
