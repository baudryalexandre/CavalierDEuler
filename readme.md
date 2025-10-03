# 🐴 Cavalier d’Euler

**Cavalier d’Euler** est une application web interactive qui illustre le célèbre problème mathématique du parcours du cavalier, également connu sous le nom de *problème du cavalier d’Euler*. Ce projet permet de visualiser et d'explorer les différentes solutions possibles de ce défi combinatoire sur un échiquier.

🔗 [Accéder à la démo en ligne](https://baudryalexandre.github.io/CavalierDEuler/)

---

## 📚 Contexte mathématique

Le problème du cavalier consiste à déplacer un cavalier sur un échiquier de manière à ce qu'il visite chaque case une seule fois, sans jamais repasser par la même case. Ce problème, étudié depuis le IXe siècle, a été analysé en profondeur par le mathématicien Leonhard Euler au XVIIIe siècle, qui a proposé des méthodes pour construire de tels parcours ([en.chessbase.com](https://en.chessbase.com/post/euler-and-the-knights-tour?utm_source=chatgpt.com)).

Ce défi est un cas particulier du problème du chemin hamiltonien en théorie des graphes, où l'on cherche un chemin passant par chaque sommet exactement une fois ([en.wikipedia.org](https://en.wikipedia.org/wiki/Knight%27s_tour?utm_source=chatgpt.com)).

---

## 🚀 Fonctionnalités

- Visualisation interactive du parcours du cavalier sur un échiquier.
- Génération de parcours ouverts ou fermés (où le cavalier revient à sa case de départ).
- Interface utilisateur intuitive pour explorer différentes solutions.

---

## 🛠️ Technologies utilisées

- **Frontend** : HTML, CSS, JavaScript
- **Backend** : Python (Flask), Go
- **Autres** : Fichiers de configuration et scripts pour la gestion du projet

---

## 📦 Installation

### Prérequis

- [Python 3.x](https://www.python.org/downloads/)
- [Go](https://golang.org/dl/)
- [Node.js](https://nodejs.org/) et [npm](https://www.npmjs.com/)

### Étapes

1. **Cloner le dépôt :**

   ```bash
   git clone https://github.com/baudryalexandre/CavalierDEuler.git
   cd CavalierDEuler
   ```

2. **Installer les dépendances Python :**

   ```bash
   pip install -r requirements.txt
   ```

3. **Installer les dépendances Node.js :**

   ```bash
   npm install
   ```

4. **Lancer le serveur :**

   - **Python :**

     ```bash
     python server.py
     ```

   - **Go :**

     ```bash
     go run main.go
     ```

5. **Accéder à l'application :**

   Ouvrir votre navigateur à l'adresse [http://localhost:5000](http://localhost:5000) ou [http://localhost:8000](http://localhost:8000) selon le serveur utilisé.

---

## 📁 Structure du projet

```
CavalierDEuler/
├── algo.py               # Algorithme de génération du parcours
├── server.py             # Serveur backend en Python
├── main.go               # Serveur backend en Go
├── index.html            # Page principale de l'application
├── public/               # Fichiers statiques (CSS, JS, images)
├── package.json          # Configuration du projet Node.js
├── go.mod                # Configuration du projet Go
└── README.md             # Documentation du projet
```

---

## 🧠 Ressources complémentaires

- [Article Wikipédia sur le problème du cavalier](https://fr.wikipedia.org/wiki/Probl%C3%A8me_du_cavalier)
- [Euler et le parcours du cavalier](https://en.chessbase.com/post/euler-and-the-knights-tour)
- [Analyse mathématique du parcours du cavalier](https://eulerarchive.maa.org/hedi/HEDI-2006-04.pdf)

---

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.

---

## 🤝 Contribuer

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une *issue* ou à soumettre une *pull request* pour proposer des améliorations ou signaler des problèmes.
