# Système de Gestion de Bibliothèque 📚

---

## 📌 Description
Ce projet est une application de gestion de bibliothèque permettant :
- **Aux utilisateurs** (étudiants/enseignants) de consulter, emprunter et rendre des livres.
- **Aux bibliothécaires** d'ajouter ou supprimer des livres du catalogue.

---

## ❓ Comment utiliser l'application

### Pour les **utilisateurs** (étudiants/enseignants) :
1. Accédez à l'interface : `python src/main.py`
2. Consultez les livres disponibles
3. Pour emprunter : 
   - Sélectionnez un livre
   - Cliquez sur "Emprunter"
4. Pour rendre un livre :
   - Allez dans "Mes emprunts"
   - Cliquez sur "Rendre"

### Pour les **bibliothécaires** :
1. Connectez-vous avec vos identifiants
2. Ajouter un livre :
   - Remplissez le formulaire "Nouveau livre"
   - Validez avec "Ajouter"
3. Supprimer un livre :
   - Cherchez le livre dans le catalogue
   - Cliquez sur "Supprimer"

---

## 🛠️ Structure du Projet
```bash
bibliotheque-systeme/
├── src/
│   ├── templates/            # Dossier pour les templates HTML
│   │   └── index.html        # Exemple de page HTML
│   ├── models/
│   │   ├── livre.py          # Classe Livre
│   │   └── utilisateur.py    # Classes Utilisateur, Étudiant, Enseignant, Bibliothécaire
│   ├── static/
│   │   └── style.css         # Fichier CSS pour le style
│   ├── main.py               # Script principal de lancement
│   └── api.py                # API pour la gestion des livres et des emprunts
├── tests/
│   └── test_emprunt.py       # Tests unitaires pour les emprunts
├── .gitignore                # Fichiers à exclure du suivi Git
├── README.md                 # Documentation du projet
└── requirements.txt          # Dépendances (optionnel)
```

---

## 🚀 Installation & Exécution
1. **Cloner le dépôt** :
   ```bash
    git clone https://github.com/votre-utilisateur/bibliotheque-systeme.git
2. **Lancer l'application** :
   ```bash
   cd bibliotheque-systeme
   python src/main.py
