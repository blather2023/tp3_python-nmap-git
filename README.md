# tp3_python-nmap-git
conception, amélioration et test d un script de scan réseau python

# OBJECTIF
crée un script python capable de lancer des scans nmap **sur 127.0.0.1 uniquement** et sauvegarder chaque rapport dans "./reports/".
# MODE D UTILISATION
# ÉTAPE1: INSTALLATION
1-  disposer d une machine kali linux

2-  Met à jour et installe les outils si besoin :

*sudo apt update

*sudo apt install -y nmap python3 

3- Crée le dossier du TP et entre dedans :

*mkdir ~/tp3-mini-scanner

*cd ~/tp3-mini-scanner

4- ajouter votre script et Faire les premiers commits :

*git add tp3_kali_scanner.py

*git commit -m "Initial commit: tp3 scanner script"

NB: faire un git int dans le dossier tp3-mini-scanner pour crée un noueau répertoire

5-  ajoute README et dossier reports vides
*echo "# TP3 - Mini Scanner" > README.md

*mkdir -p reports

*git add README.md reports

*git commit -m "Ajout README et dossier reports"

6- au fure et a mésure améliorer le script  et enrégistrer le à l aide des commits

*git commit -am (ex:"Amélioration menu + messages d'état")

# ÉTAPE2: Éxécution et résultat

1- utiliser votre machine kali linux, à l aide du terminal exécuter:

*python3 tp3_kali_scanner.py

2- faites un choix parmi les option du ménue

3- et saisisez l adresse 127.0.0.1 ou localhost ou personnalisé à l aide d option (-p 1-1024 -sV)

4- vous retrouvez les rapports des scans dans le dossier ./reports/ sous forme TXT. par exemple:
top100_20251114_223015.txt

VOUS TROUVEREZ LES DIFFÉRENTES VERSIONS PRÉCÉDENTE DU PROJET DANS LE REPERTOIRE DE DÉPOT DU PROJET

MERCI POUR VOTRE COLLABORATION!!!!!!
