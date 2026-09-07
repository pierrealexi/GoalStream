# MonProjet

Ce dépôt centralise les deux parties du projet : front-end (Next.js) et back-end (Go).

---

## Prérequis

- [Node.js](https://nodejs.org/) 18+ (pour Next.js)  
- [Go](https://golang.org/) 1.21+ (pour le back-end)  
- [Docker](https://www.docker.com/) (optionnel pour lancer le projet complet)  
- [Git](https://git-scm.com/)  

---

## Structure du projet

MonProjet/
│-- frontend/ # Submodule Next.js
│-- backend/ # Submodule Go
│-- docs/ Submodule docs
│-- README.md
│-- docker-compose.yml (optionnel)


- `frontend/` : code Next.js  
- `backend/` : code Go
- `docs/` : documentation
- Les deux sont des **submodules Git**.

---

## Cloner le projet

Pour cloner le projet avec les submodules :

```bash
git clone --recurse-submodules https://github.com/toncompte/MonProjet.git
cd MonProjet
```

Si tu as déjà cloné sans --recurse-submodules :

```bash
git submodule update --init --recursive
```
