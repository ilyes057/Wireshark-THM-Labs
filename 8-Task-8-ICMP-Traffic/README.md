# 📡 Task 8 - Analyse ICMP (Wireshark 101)

## 🔍 Analyse des Paquets ICMP

### 📌 Paquet 4 (Requête ICMP - Type 8)
![Requête ICMP Type 8](screenshots/question-1.png)  
- **Type** : 8 (Requête ICMP)  
- **Signification** : Ping (echo request) envoyé à un serveur  
- **Analyse** :  
  Paquet standard d'une requête ping, attend une réponse (Type=0).  

### 📌 Paquet 5 (Réponse ICMP - Type 0)
![Réponse ICMP Type 0](screenshots/question-2.PNG)  
- **Type** : 0 (Réponse ICMP)  
- **Signification** : Réponse à un ping (echo reply)  
- **Analyse** :  
  Confirme que le serveur a bien répondu à la requête.  

### 📌 Paquet 12 (Timestamp)
![Timestamp ICMP](screenshots/question-3.PNG)  
- **Date** : May 30, 2013  
- **Format** : Timestamp UNIX converti  
- **Utilité** :  
  Permet de détecter des anomalies temporelles (ex: délais anormaux).  

### 📌 Paquet 18 (Data String)
![Data ICMP](screenshots/question-4.PNG)  
- **Payload** : `08090a0b0c0d0e0f101112131415161718191a1b1c1d1e1f202122232425262728292a2b2c2d2e2f3031323334353637`  
- **Format** : Hexadécimal  
- **Analyse** :  
  Données aléatoires typiques d'un ping standard.  

## 📚 Fichiers Inclus
- [Capture complète](captures/task8.pcap)  
- [Réponses THM](answers.txt)  