# Hacker2108 Tracer

Hacker2108 Tracer est un outil Python conçu pour recueillir des informations à partir d'adresses IP, de numéros de téléphone et de noms d'utilisateur sur diverses plateformes de médias sociaux. Il fournit des détails tels que la géolocalisation IP, les informations sur l'opérateur téléphonique et les profils de médias sociaux.

## Fonctionnalités

* **Suivi IP (IP Tracker) :** Récupère des informations détaillées sur une adresse IP, y compris la localisation, le fournisseur d'accès Internet (FAI), et plus encore.
* **Afficher votre IP (Show Your IP) :** Affiche votre adresse IP publique.
* **Suivi de numéro de téléphone (Phone Number Tracker) :** Obtient des informations sur un numéro de téléphone, telles que l'opérateur, la localisation et le fuseau horaire.
* **Suivi de nom d'utilisateur (Username Tracker) :** Recherche des noms d'utilisateur sur plusieurs plateformes de médias sociaux.

## Installation

1.  **Clonez le dépôt :**

    ```bash
    git clone [https://github.com/hacker2108-maker/Hacker2108-tracer.git](https://github.com/hacker2108-maker/Hacker2108-tracer.git)
    ```

2.  **Assurez-vous d'avoir Python 3.x installé :**

    * Sur Linux/macOS :

        ```bash
        python3 --version
        ```

        Si Python 3 n'est pas installé, installez-le à partir de [python.org](https://www.python.org/downloads/).

    * Sur Windows :

        Téléchargez et installez Python 3.x depuis [python.org](https://www.python.org/downloads/).

3.  **Installez les bibliothèques Python requises :**

    ```bash
    pip install requests phonenumbers
    ```

    * Si `pip` n'est pas installé, vous devrez peut-être l'installer :

        * Sur Linux/macOS :

            ```bash
            sudo apt update # Pour les systèmes basés sur Debian/Ubuntu
            sudo apt install python3-pip
            ```

            ou

            ```bash
            sudo yum update # Pour les systèmes basés sur CentOS/Fedora
            sudo yum install python3-pip
            ```

        * Sur Windows :

            `pip` est généralement inclus avec l'installation de Python. Si ce n'est pas le cas, assurez-vous de cocher la case "Ajouter Python au PATH" lors de l'installation de Python.

## Utilisation

1.  **Exécutez le script :**

    ```bash
    python <nom_de_votre_script>.py
    ```

2.  Sélectionnez une option dans le menu.
3.  Entrez les informations demandées (adresse IP, numéro de téléphone, nom d'utilisateur).

## Exemples

* **Suivi d'adresse IP :**

    ```
    Entrez l'adresse IP cible : 8.8.8.8
    ```

* **Suivi de numéro de téléphone :**

    ```
    Entrez le numéro de téléphone cible Ex [+6281xxxxxxxxx] : +15551234567
    ```

* **Suivi de nom d'utilisateur :**

    ```
    Entrez le nom d'utilisateur : exemple_utilisateur
    ```

## Limitations

* La précision des informations récupérées dépend des API utilisées.
* Certaines informations peuvent ne pas être disponibles pour toutes les adresses IP, numéros de téléphone ou noms d'utilisateur.
* Cet outil est fourni à des fins d'information uniquement. Une utilisation abusive peut entraîner des conséquences juridiques.

## Avertissement

Cet outil est destiné à des fins éducatives et informatives uniquement. L'auteur n'est pas responsable de toute utilisation abusive. Utilisez-le de manière responsable et éthique.

## Contribution

Les contributions sont les bienvenues ! Si vous souhaitez contribuer :

1.  Forkez le dépôt : [https://github.com/hacker2108-maker/Hacker2108-tracer.git](https://github.com/hacker2108-maker/Hacker2108-tracer.git)
2.  Créez une nouvelle branche pour votre fonctionnalité ou correction de bug.
3.  Validez vos modifications.
4.  Poussez vers la branche.
5.  Soumettez une demande de tirage.

Veuillez mentionner mon compte GitHub si vous utilisez ce code.

## Licence

Ce projet est sous licence MIT - consultez le fichier [LICENSE](LICENSE) pour plus de détails.

## Auteur

hacker2108-maker - [https://github.com/hacker2108-maker/](https://github.com/hacker2108-maker/)

## Remerciements

* Merci aux développeurs des bibliothèques `requests` et `phonenumbers`.
* Tous les fournisseurs d'API que le programme utilise.

**Principales modifications :**

* Le lien du dépôt a été ajouté de manière cohérente dans la section "Contribution".
* Le lien du dépôt a été mis à jour dans la section "Installation".

J'espère que cela répond à vos besoins et fournit des instructions complètes pour installer et exécuter votre outil sans problème !
