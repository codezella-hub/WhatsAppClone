# 📱 WhatsAppClone

Clone d’une application de messagerie instantanée inspirée de **WhatsApp**, permettant la communication en temps réel entre utilisateurs avec gestion des médias et une interface moderne.

---

## 🚀 Fonctionnalités

- ✅ Authentification des utilisateurs
- ✅ Chat en temps réel (messages texte, médias)
- ✅ Upload et stockage des fichiers utilisateurs
- ✅ Groupes de discussion (prévu)
- ✅ Interface utilisateur responsive
- ✅ Déploiement avec **Docker Compose**

---

## 🛠️ Stack technique

- **Frontend (UI)** : TypeScript, HTML, SCSS  
- **Backend** : Java (Spring Boot)  
- **Base de données** : (à préciser – MySQL, PostgreSQL ou MongoDB)  
- **Temps réel** : WebSocket / Socket.io (selon implémentation)  
- **Conteneurisation** : Docker & Docker Compose  

---

## ⚙️ Installation et lancement

### 1️⃣ Cloner le projet
```bash
git clone https://github.com/codezella-hub/WhatsAppClone.git
cd WhatsAppClone
```

### 2️⃣ Lancer avec Docker
Assurez-vous d’avoir **Docker** et **Docker Compose** installés.  
Puis lancez :
```bash
docker-compose up --build
```

### 3️⃣ Démarrage manuel (sans Docker)
#### Backend
```bash
cd whatsappclone
./mvnw spring-boot:run
```

#### Frontend
```bash
cd whatsapp-clone-ui
npm install
npm start
```

---

## ▶️ Utilisation

- UI accessible sur : [http://localhost:4200](http://localhost:4200)  
- API backend disponible sur : [http://localhost:8089](http://localhost:8089)  

Exemples de fonctionnalités :
- 📩 Envoyer un message en temps réel
- 📤 Partager des images et vidéos
- 👥 Créer des conversations privées ou de groupe

---

## 📂 Structure du projet

```
WhatsAppClone/
│── whatsapp-clone-ui/       # Frontend (TypeScript, SCSS, HTML)
│── whatsappclone/           # Backend (Java Spring Boot)
│── uploads/users/           # Stockage des fichiers utilisateurs
│── docker-compose.yml       # Orchestration conteneurs
│── README.md                # Documentation
```

---

## ✅ Tests

### Backend (Java)
```bash
cd whatsappclone
./mvnw test
```

### Frontend (TypeScript)
```bash
cd whatsapp-clone-ui
npm test
```

---

## 🚀 Déploiement

Le projet peut être déployé sur n’importe quel serveur supportant **Docker**.  
Exemple :  
```bash
docker-compose -f docker-compose.prod.yml up -d
```

👉 Possibilité future : déploiement via **GitHub Actions + Render/Heroku/AWS**.

---

## 🤝 Contribution

Les contributions sont les bienvenues !  

1. **Fork** le projet  
2. Crée une nouvelle branche :  
   ```bash
   git checkout -b feature/ma-fonctionnalite
   ```
3. Commit tes modifications :  
   ```bash
   git commit -m "Ajout de ma fonctionnalité"
   ```
4. Push ta branche :  
   ```bash
   git push origin feature/ma-fonctionnalite
   ```
5. Ouvre une **Pull Request**

---

## 📄 Licence

À préciser (MIT, Apache 2.0, GPL…).  
👉 Exemple :  

```
MIT License
```

---

## 👨‍💻 Auteur

- **Codezella Hub**  
  🔗 [GitHub](https://github.com/codezella-hub)  

---

✨ Bon développement & amuse-toi avec ce clone de WhatsApp !
