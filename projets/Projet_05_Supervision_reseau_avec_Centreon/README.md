## Projet 5 : Supervision réseau avec Centreon

🎯 **Objectif :** Surveiller l’état de machines sur un réseau.

🛠️ **Étapes à réaliser :**
- Installation d’un Linux (Debian/Ubuntu)
- Installation de Centreon (https://docs.centreon.com/docs/)
- Surveillance de machines : ping, CPU, mémoire, stockage
- Alertes en cas d’incident

📚 **Compétences travaillées :** Supervision, alerte, ressources système, Centreon

🕓 **Durée estimée :** 3-4 jours

### 📝 Fiche projet

1. Nom du projet : Supervision réseau avec Centreon
2. Date de réalisation : 14/04/2025
3. Objectif du projet : Surveiller l’état de machines sur un réseau.
4. Matériel utilisé : vm Debian / logiciel centreon
5. **Étapes réalisées :**  
      creation de la VM debian depuis le projet 1 
      Pour installer centréon j'ai dans un premier temps mis a jour debian avec la commande
      ( sudo apt update && sudo apt full-upgrade -y )
      Ensute j'ai installer les dépendances nécessaire au functionnement de Centréon
      le Paket d'installation du logiciel centreon n'ai pas functionnel il faut donc monter une autre Vm avec l'iso fournit par centreon
      c'est ce que j'ai fait créer la vm avec l'iso fournit dans la doc un vm pour vmware prémonté 
      je n'avais cas suivre les instruction de paramétrage comme la timeZone (Europe/ Paris ) et le nom de l'host (Thomas-monitoring)
      petite difficulté je ne c'est pas quelle option de Network Adapter selectionner en fonction du reseau (demander a max)
      l'ajout de l'ip pour avoir un retour d'information sur le reseau 
      
      *(Inclure des captures si possible)*
6. **Difficultés rencontrées :**
      j'ai rencontré mon premier problemme parce que le user que j'ai créer sur ma machine virtuel n'ai pas sudeur (n'a pas les access)
      je vais donc l'ajouter au fichier en qestion afin d'avoir les access complet pour cela je vais me connecter avec le user root pour pouvoir édidté le fichier  
      et ajouter le tout les users 
7. **Ce que j’ai appris :**
8. **Améliorations possibles :**
