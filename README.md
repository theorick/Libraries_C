# 📦 Centralisateur de Librairies C

Ce projet centralise les **librairies C les plus utiles et populaires** pour le développement général, scientifique, réseau, graphique et traitement de données.  
L’objectif est de faciliter la configuration d’un environnement C complet.

---

## ⚡ Librairies Incluses

### 🔹 Développement général
- **glib** – Collections, utilitaires et structures de données  
- **libconfig** – Gestion de fichiers de configuration  
- **argp** – Parsing d’arguments de la ligne de commande  

### 🔹 Mathématiques & Scientifique
- **GSL (GNU Scientific Library)** – Fonctions mathématiques avancées  
- **GMP / MPFR** – Arithmétique de précision multiple  

### 🔹 Réseau & Protocoles
- **libcurl** – Requêtes HTTP et FTP  
- **libwebsockets** – WebSockets  
- **OpenSSL** – Cryptographie et HTTPS  

### 🔹 Développement graphique / Jeux
- **SDL2** – Création de jeux et interfaces graphiques  
- **SFML** – Multimédia et jeux (C++ mais utilisable avec C)  
- **ncurses** – Interface texte avancée dans le terminal  

### 🔹 JSON / XML / Fichiers
- **cJSON** – Parsing JSON  
- **libxml2** – Parsing XML  
- **protobuf-c** – Protocol Buffers pour C  

---

## 🚀 Installation

### 1️⃣ Linux (Ubuntu/Debian)
```bash
sudo apt update
sudo apt install build-essential cmake git
sudo apt install libglib2.0-dev libcurl4-openssl-dev libssl-dev libgsl-dev libsdl2-dev libncurses5-dev libxml2-dev

---

2️⃣ macOS (Homebrew)
brew update
brew install glib curl openssl gsl sdl2 ncurses libxml2


3️⃣ Compiler un exemple
gcc examples/hello.c -o hello -lcurl -lssl -lcrypto -lgsl -lglib-2.0
./hello


---

## Contribution

Vous pouvez contribuer facilement :  
1. Fork le repo  
2. Crée une branche `feature/xxx`  
3. Ajoute votre librairie ou correction  
4. Ouvre une Pull Request  

---

## Star

Si ce hub vous est utile, **mettez une étoile ⭐** pour soutenir le projet et aider la communauté !
