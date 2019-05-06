# 1. fonctionnalités desirés
    Le projet consiste à développer one et emailing. Ce développement comprend diverses tâches toutes très consistantes. Parmi ces tâches (et en dehors des évolutions en performance) :
    
    * Le GDPR
    * L’emailing générique
    * La convergence vers des applications de G2 (étant avant les X-App), c’est-à-dire travailler de manière identique (transversalité) quel que soit l’applicatif, et en particulier pour :
        * Étape 1 :
            * La gestion des listes
            * L’éditeur HTML
            * Les users (utilisateurs et rôles)
        * Étape 2
            * L’emailing générique
            * La population
            * La bibliothèque / les modèles
        * Étape 3
            * L’approbation
            * L’intégration des ressources media
        * La gestion élaborée de la population et en particulier,
            * Le dédoublonnage
            * Le profilage et la gestion des champs (obligatoire/facultatif – privé / public) (system et communautaire = rubriques libres)
            * Les groupes formels (system et importés) et informels (customisés par communauté)
            * Le regroupement naturel par cabinet
            * La gestion de cible au sein de la population (au départ des outils de profilage)
            * Le dashboard population
            * L’import automation
        * Le marketing automation et en particulier,
           *  La gestion des landing pages et du short coding d’un URL (tracking et autologin)
            * La création de campagnes

# 2. Diagramme de cas d'utilisation:
## 2.1 Definition des acteurs:
Dans notre système, on peut avoir deux acteurs qui interagissent avec l’application:
* Un utilisateur humain qui’est le client de la plateforme avec les privilèges d’administrateur, il organise les formations des expertises comptables. L’utilisateur principal de l’application, il organise des formations des expertises comptables, une personne qualifiée dans le domaine fiduciaire, généralement un membre représente l’IEC (Institut des Experts-comptables et des Conseils fiscaux), il doit avoir les privilèges «Admin» l’application lui permet de notifier les différents contacts de la plateforme des formations et événements existants, aussi les orateurs, les exposants ainsi que les différents invités. l’application lui permet aussi de suivre les différentes statistiques sur ces e-mails ( suivi des e-mails, nombre de vue, mails inactives, spams, retours...).
* Une autre application de l'ecosysteme Tamtam qui desire utilisé le service d'emailing.