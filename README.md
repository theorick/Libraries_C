# 📦 Centralisateur de Librairies C

Ce projet centralise les **librairies C les plus utiles et populaires** pour le développement général, scientifique, réseau, graphique, cryptographie et traitement de données.  
L’objectif est de fournir un **référentiel complet** pour installer rapidement un environnement C complet.

---

## ⚡ Librairies Incluses (~50)

### 🔹 Développement général
- **glib** – Collections, utilitaires et structures de données  
- **libconfig** – Fichiers de configuration  
- **argp** – Parsing d’arguments  
- **libuuid** – Gestion des UUID  
- **libarchive** – Manipulation d’archives (.tar, .zip…)  
- **zlib** – Compression de données  
- **bzip2** – Compression avancée  
- **lz4** – Compression ultra-rapide  
- **libffi** – Interface de fonctions dynamiques  
- **libsqlite3** – Base de données embarquée  

### 🔹 Mathématiques & Scientifique
- **GSL (GNU Scientific Library)** – Maths avancées  
- **GMP** – Entiers de précision arbitraire  
- **MPFR** – Flottants de précision multiple  
- **Armadillo (C++)** – Algèbre linéaire (compatible C++)  
- **BLAS / LAPACK** – Calculs matriciels  
- **FFTW** – Transformée de Fourier rapide  
- **OpenBLAS** – BLAS optimisé  
- **Eigen (C++)** – Algèbre linéaire rapide  
- **Cephes** – Fonctions mathématiques spéciales  
- **NLopt** – Optimisation numérique  

### 🔹 Réseau & Protocoles
- **libcurl** – HTTP, FTP, etc.  
- **libwebsockets** – WebSockets  
- **OpenSSL** – Cryptographie  
- **libssh2** – SSH client  
- **libmqtt** – MQTT protocol  
- **libxml2** – XML parsing  
- **libxslt** – Transformation XSLT  
- **jansson** – JSON parsing  
- **cJSON** – JSON léger  
- **protobuf-c** – Protocol Buffers  

### 🔹 Développement graphique / Multimédia
- **SDL2** – Jeux et interfaces graphiques  
- **SDL2_image** – Gestion d’images  
- **SDL2_mixer** – Audio  
- **SDL2_ttf** – Textes  
- **SFML (C++)** – Multimédia  
- **ncurses** – Terminal avancé  
- **Allegro 5** – Graphiques et jeux  
- **OpenGL** – Graphiques 3D  
- **GLEW** – Gestion extensions OpenGL  
- **GLFW** – Fenêtres et contextes OpenGL  

### 🔹 Compression / Fichiers
- **libzip** – ZIP  
- **lib7zip** – 7zip  
- **xz-utils / liblzma** – Compression LZMA  
- **brotli** – Compression moderne  
- **zstd** – Compression très rapide  
- **libpng** – Images PNG  
- **libjpeg** – Images JPEG  
- **libtiff** – Images TIFF  
- **libwebp** – Images WebP  
- **OpenEXR** – Images HDR  

---

## 🚀 Installation

### 1️⃣ Linux (Ubuntu/Debian)
```bash
sudo apt update
sudo apt install build-essential cmake git \
libglib2.0-dev libcurl4-openssl-dev libssl-dev libgsl-dev \
libsdl2-dev libsdl2-image-dev libsdl2-mixer-dev libsdl2-ttf-dev \
libncurses5-dev libxml2-dev libjpeg-dev libpng-dev libtiff-dev zlib1g-dev \
libffi-dev libsqlite3-dev libbz2-dev liblzma-dev libwebp-dev

---

2️⃣ macOS (Homebrew)
brew update
brew install glib curl openssl gsl sdl2 ncurses libxml2


3️⃣ Compiler un exemple
gcc examples/hello.c -o hello -lcurl -lssl -lcrypto -lgsl -lglib-2.0
./hello
```

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
