# 🔒 Cyber Kill Chain – Comprendre les étapes d'une cyberattaque (avec des analogies simples)

> 📌 **But du document** : Comprendre les étapes d'une attaque informatique selon le modèle **Cyber Kill Chain** proposé par Lockheed Martin, en les **expliquant simplement**, avec des **analogies de la vie quotidienne**.

---

## 🧠 C’est quoi le Cyber Kill Chain ?

La **Cyber Kill Chain** est un modèle qui décrit **chaque étape d'une cyberattaque** réussie. Comprendre ce processus aide les professionnels de la cybersécurité à **détecter, bloquer et réagir** à chaque phase.

> 🧪 **Analogie globale** : C’est comme **un cambrioleur** qui veut voler quelque chose chez vous. Il ne va pas entrer par magie dans votre salon. Il suit des étapes, tout comme un attaquant informatique.

---

## 🧱 Les 7 étapes du Cyber Kill Chain

### 1. 🕵️‍♂️ Reconnaissance (Reconnaissance)

**But :** L'attaquant collecte des informations sur la cible (adresses IP, employés, technologies utilisées, etc.)

**Analogie :** Comme un voleur qui observe votre maison à distance : il regarde à quelle heure vous partez, où est la caméra, combien d’étages…

**Exemples techniques :**
- Recherche sur les réseaux sociaux
- Scan réseau (Nmap, Shodan)
- Whois, DNS, Google dorking

---

### 2. 💣 Armes / Préparation (Weaponization)

**But :** L'attaquant prépare son outil malveillant (ex : un malware intégré dans un fichier Word piégé).

**Analogie :** Le cambrioleur fabrique un faux badge d’accès ou un outil pour ouvrir la serrure sans alarme.

**Exemples techniques :**
- Création d’un malware
- Exploit pack, PDF piégé, macro Word
- Lien vers un site infecté

---

### 3. 📬 Livraison (Delivery)

**But :** L’attaquant envoie le fichier malveillant à la victime.

**Analogie :** Le voleur glisse une lettre piégée dans votre boîte aux lettres ou vous donne un colis infecté.

**Exemples techniques :**
- Email de phishing
- Lien piégé
- Clé USB abandonnée

---

### 4. 💥 Exploitation (Exploitation)

**But :** Une fois ouvert, le malware exploite une faille pour s’installer ou s'exécuter.

**Analogie :** Vous ouvrez la porte au faux livreur : il en profite pour désactiver l’alarme ou entrer sans permission.

**Exemples techniques :**
- Exploitation d'une faille 0-day
- Exécution d’un script malveillant
- Autorisation d’exécuter une macro

---

### 5. 🛠️ Installation (Installation)

**But :** Le malware s’installe dans le système pour rester discret et persister.

**Analogie :** Le cambrioleur cache une caméra dans votre maison pour surveiller sans se faire voir.

**Exemples techniques :**
- Implantation d’un cheval de Troie (trojan)
- Modification du registre Windows
- Création d’un service ou processus caché

---

### 6. 🎮 Commandement & Contrôle (C2) (Command & Control)

**But :** L’attaquant prend le contrôle du système à distance.

**Analogie :** Le voleur utilise la caméra pour savoir quand vous êtes absent et active à distance des outils pour voler.

**Exemples techniques :**
- Connexion à un serveur distant
- Communication chiffrée entre la machine infectée et le hacker
- Tunneling de données

---

### 7. 🧨 Actions sur Objectifs (Actions on Objectives)

**But :** L’attaquant atteint son objectif final : vol de données, sabotage, espionnage, etc.

**Analogie :** Le voleur vole votre télé, vos documents, ou laisse un message sur le mur.

**Exemples techniques :**
- Vol de fichiers sensibles
- Suppression de données
- Ransomware
- Escalade de privilèges

---

## 🔁 Pourquoi c’est utile de connaître cette chaîne ?

✅ Pour **détecter une attaque à temps** (par exemple dès la phase de reconnaissance)  
✅ Pour **renforcer la défense** à chaque niveau  
✅ Pour **mieux réagir** : si tu sais où tu en es dans la chaîne, tu peux mieux contrer l’attaque

---

## 🛡️ Exemple défensif

| Étape            | Mesure défensive possible             |
|------------------|----------------------------------------|
| Reconnaissance   | Firewall, IDS, politique DNS           |
| Delivery         | Antispam, antivirus, sandbox           |
| Exploitation     | Mises à jour régulières, EMET          |
| C2               | IDS/IPS, détection de trafic anormal   |
| Actions finales  | DLP (Data Loss Prevention), segmentation réseau |


