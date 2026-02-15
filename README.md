# DDoS Tool - Outil d'Attaque DDoS

## 🚀 Installation

```bash
npm install
```

## ⚡ Utilisation

```bash
node index.js
```

## 🎯 Comment ça marche

1. **Démarrage** : Lancez l'outil avec `node index.js`
2. **Cible** : Entrez l'URL ou IP du site à attaquer
3. **Puissance** : Choisissez le nombre de requêtes par seconde (défaut: 50,000)
4. **Attaque** : L'outil lance automatiquement 17 vecteurs d'attaque simultanés

## 💥 Vecteurs d'Attaque

- **HTTP GET Flood** : Requêtes GET ultra-rapides
- **POST Flood** : Données massives pour épuiser la mémoire
- **HEAD Flood** : Épuisement des connexions
- **PUT Flood** : Overload CPU avec JSON
- **OPTIONS Flood** : Destruction du router
- **PATCH Flood** : Attaques de modification
- **DELETE Flood** : Tentatives de suppression
- **TRACE Flood** : Drain des ressources de debug
- **CUSTOM Flood** : Méthodes personnalisées
- **SSL/TLS Exhaustion** : Épuisement des certificats
- **Raw Connections** : Sockets TCP bruts
- **HTTP/2 Flood** : Protocole moderne
- **DNS Flood** : Épuisement DNS
- **Parallel Attacks** : 10 instances parallèles
- **Cluster Workers** : Multi-processus par CPU core
- **Promise.all Flood** : 50 requêtes simultanées

## 📊 Statistiques en Temps Réel

- **REQUÊTES** : Nombre de requêtes réussies
- **ERREURS** : Nombre d'échecs (timeouts, etc.)
- **TOTAL** : Requêtes + Erreurs
- **OVERLOAD** : Requêtes par seconde réelles

## ⚙️ Configuration

- **Timeouts** : 1-100ms pour maximum d'impact
- **Multi-threading** : Utilise tous les cores CPU disponibles
- **Auto-formatage** : Ajoute automatiquement `https://` si besoin

## 🔥 Performance

- **Base** : 50,000 req/sec par défaut
- **Maximum** : 4,000,000+ req/sec avec tous les vecteurs
- **Impact** : CPU, mémoire, réseau, router simultanément

## ⚠️ Arrêt

Appuyez sur `Ctrl+C` pour arrêter proprement l'attaque

## 🛡️ Protection

Le code est obfusqué avec :
- Chiffrement RC4 des chaînes
- Protection anti-debug
- Brouillage du flux de contrôle
- Code mort aléatoire
- Auto-défense contre la modification

---

**⚠️ Avertissement :** À usage éducatif uniquement. Utilisation responsable requise.
