-- 4.4.0b --

* Facilitation d'accès à certaines fonctions de Miner Helper pour les plugins
* Amélioration de la gestion de la mémoire afin de limiter les crash
* Ajout de contrôles pour éviter certains crash
* Ajout de message de debug dans les logs


-- 4.3.0b --

* Ajout d'un assistant d'aide à la création de configuration de minage
* Correction des doublons de protocoles sur le contrôle à distance lors de la création d'une nouvelle configuration


-- 4.2.1b --

* Correction de quelques bugs mineurs sur le contrôles à distance


-- 4.2.0b --

* Ajout d'un système de statistique pour aider à l'amélioration de Miner Helper, avec demande d'autorisation de l'utilisateur au tout premier lancement
* Ajout de la possibilité de modifier la température maximum des GPU dans la configuration avancée
* Ajout de la possibilité pour l'utilisateur d'affiché le numéro de série de son installation de Miner Helper
* Correction du bug qui sélectionnait le "stratum+tc://" comme protocole à la place de "stratum+tcp://"


-- 4.1.3b --

* Corection d'un bug qui créer des doublons dans les listes de sélection des protocoles et des algorithmes sur la page de listage des pools


-- 4.1.2b --

* Correction de l'actualisation des plugins


-- 4.1.1b --

* Correction du bug du chargement des couleurs des skins sur certaines fenêtres
* Correction d'un bug sur le chargement de la liste des scripts
* Correction de l'inversion entre "enregistrer configuration" et "enregistrer configuration sous"


-- 4.1.0b --

* Ajout d'un message lorsque l'UPNP n'est pas disponible lors du démarrage du contrôle à distance
* Ajout d'un message lors de l'enregistrement d'une configuration ou lors du démarrage du minage si aucun protocole de pool n'a été sélectionné
* Ajout de la vérification que seul des nombre sont bien entrés dans le port de pool et ajout d'un message en cas de copier/coller de texte dans le port de pool
* Modification de l'interface au niveau de la page de configuration
* Modification du système de skin suite à la modification de la page de configuration
* Mise à jour des différents skins fourni avec Miner Helper


-- 4.0.0b --

* Refonte totale de l'interface
* Modification et amélioration du système de skin du à la reonte de l'interface
* Ajout de trois nouveaux skins en plus du nouveau skin par défaut
* Amélioration de la gestion des adresses de pool dans le cas où un protocole et/ou un port soit entré avec l'adresse de pool
* Modification de ce qui est était anciennement appelé "wallet" pour "configuration de minage"
* Modification de la fonction switchTab() du langage de script pour s'adapter à la refonte de l'interface


-- 3.7.2b --

* Ajout de l'affichage de la la ligne de commande, dans l'onglet "Mineur", que Miner Helper utilise lors du minage
* Ajout de nouveaux contrôles d'erreurs pour tenté d'éviter les fermetures subites de Miner Helper lors du minage
* Correction d'un bug se manivestant aléatoirement lors de la sauvegarde d'un wallet
* Correction du bug qui faisait que des infos continuaientt à être affiché même après l'arrêt du minage


-- 3.7.1b --

* Correction d'un bug pouvant parfois empêcher le démarrage du mining ou sa sortie de correctement s'afficher


-- 3.7.0b --

* Ajout d'une aide sur l'onglet "Gestion wallets"
* Ajout de la possibilité de ré-activer les options avancées de minage depuis le sous onglet de configuration "Avancé"


-- 3.6.1b --

* Ajout de scrollbars afin de pouvoir faire défiler les pages d'aide des onglets de configuration


-- 3.6.0b --

* Ajout de différentes pages d'aide pour les sous onglet de l'onglet de configuration
* Ajout d'une vérification de présence du processus du soft de mining en cas de non lancement dû par exemple à une erreur de fonctionnement du soft de mining
* Ajout de la vérification de la version minimum requise du .NET Framwork pour un fonctionnement optimal de Miner Helper


-- 3.5.2b --

* Correction des options de l'onglet "Configuration" qui n'étaient plus correctement appliquées.


-- 3.5.1b --

* Correction de l'affichage de la liste des pools qui pouvait parfois affiché un même pool plusieurs fois de suite


-- 3.5.0b --

* Ajout de messages lors de la mise à jour de la liste des pools indiquant que cette dernière a bien été effectuée ou si elle a échouée
* L'affichage des températures des GPUs a été déplacé sur l'onglet "Mineur" pour une meilleur visibilité lors du minage
* L'onglet "Configuration" a été divisé en 4 sous onglets pour plus de clareté
* Correction d'un bug qui faisait que les soft de mining et les algos apparaissaient en double après la mise à jour des softs de mining
* Correction d'un bug qui faisait que même les scripts désactivés étaient chargés


-- 3.4.0b --

* Ajout de la possibilité de mettre la liste des pools à jour
* Ajout de la possibilité de configuration le formatage des logs et le formatage du nom des fichiers de logs pour les logs des soft de mining
* Ajout de la possibilité d'activer ou de désactiver les logs des soft de mining depuis l'onglet configuration
* Modification du menu de mise à jour pour intégrer tout les sous menu de mise à jour
* Suppression du menu "Option" devenu inutile


-- 3.3.3b --

* La sortie des soft de mining est maintenant tronquée afin d'éviter des crashs dû à un soucis de mémoire surchargée
* Chaque session de mining génère maintenant un nouveau fichier log afin de pouvoir voir la sortie complète de la session de minage
* Suppression du menu contextuel de la sortie des soft de mining, devenu inutile avec ces changements


-- 3.2.2b --

* Ajout d'un champs indiquant si le pool nécessite un login et mot de passe sur la liste des pools
* Les skins sont maintenant correctement appliqués à la fenêtre de liste des pools


-- 3.2.1b --

* Correction d'un léger bug


-- 3.2.0b --

* Ajout d'un gestionnaire de pools afin de proposé directement aux utilisateurs un choix de pool selon l'algorithme et/ou le protocole
* Ajout de nouveaux contrôles pour empêcher les crash de Miner Helper dans certaines circonstances
* Ajout de nouveaux messages de debugs dans les logs


-- 3.1.3b --

* Ajout de la fonction getCoinValue() au langage de script
* Correction d'un bug qui empêchait les scripts de pouvoir fonctionner correctement


-- 3.1.2b --

* Ajout de nouveaux contrôles pour tenter d'évité de potentiel crash non gérer dans certaines conditions de matériel instable
* Ajout de nouveaux messages de debugs en cas d'erreurs
* Meilleure gestion des différentes méthodes de fermeture afin que Miner Helper se ferme toujours correctement
* Correction du choix "Quitter" dans le menu "Fichier" qui quittait Miner Helper sans proposé le choix entre la réduction et quitter * complètement l'application


-- 3.1.1b --

* Légère amélioration du système d'intégration des soft de mining
* Mise à jour des protocoles de pool


-- 3.1.0b --

* Nouveau système de gestion des protocoles de pool et meilleure gestion des champs de sasie optionnels ou non selon les protocoles de pool


-- 3.0.9b --

* Correction de 6 bugs pouvant causé le crash de Miner Helper


-- 3.0.8b --

* Correction d'un bug empêchant l'enregistrement de nouveaux wallets


-- 3.0.7b --

* Correction de 2 bugs pouvant causé le crash de Miner Helper


-- 3.0.6b --

* Ajout de la possibilité d'écrire en couleur sur la sortie des soft de mining
* Remplacement de SevenZipExtractor par des algorithmes propre à Miner Helper


-- 3.0.5b --

* Amélioration de l'intégration des soft de mining


-- 3.0.4b --

* Ajout d'un message au lancement de Miner Helper en cas de non détection de GPU compatible avec le mining
* Ajout de la possibilité de lancé une seconde instance de Miner Helper avec le paramètres --multi-sessions afin de pouvoir miner avec le CPU en plus des GPU
* Optimisation de l'accès aux fichiers de langue (supression du système de LOCKED_FILE)
* Correction de 2 bugs pouvant entrainer le crash de Miner Helper dans certaines circonstances


-- 3.0.3b --

* Maintenant à côté du nom de chaque soft de mining sera affiché aussi la version du soft
* Ajout de la fonction OnIntensityClick() au langage de script de Miner Helper
* Tous les fichiers .ini seront maintenant dans un répertoire nômé config/
* Correction d'un bug qui causait la fermeture de Miner Helper si on tentait de l'ouvrir une seconde fois
* Correction de MinerHelper.updater.exe qui parfois ne décompressais pas correctement tous les fichiers de mise à jour


-- 3.0.2b --

* Correction définitive du problème de dll de la version 3.xb


-- 3.0.1b --

* Corrige des erreurs rencontrés par certains utilisateurs avec la version 3.0.0b


-- 3.0.0b --

* Ajout de la gestion de l'intensity lors de la création d'un nouveau wallet via le contrôle à distance
* Le switch rapide (quand activé) est maintenant automatiquement mis à jour lors de la création d'un nouveau wallet depuis le contrôle à distance
* Le système d'intégration des softs de ming a été totalement revue afin qu'une majorité de soft puisse être intégré à Miner Helper sans avoir besoin de mettre Miner Helper lui même à jour
* Ajout de la fonction getMinersForAlgo() au langage de script permettant de récupérer les soft de mining pour miner un algo en particulier prend l'algo en question en paramètres
* Ajout de la fonction createWallet() au langage de script permettant de créer un nouveau wallet selon les paramètres fourni en arguments. Renvoie True en cas de réussite et False le cas échéant
* L'onglet "Manuel/Aide" été, pour le moment, temporairement, désactivé car il n'était pas très util du fait qu'il n'était plus maintenu à jour du faitde l'évolution constante de Miner Helper
* Le champs de saisie de l'adresse mail se trouve maintenant dans l'onglet configuration avec le champs de login et de nom du worker
* Mise à jour du template "default" du contrôle à distance suite aux différentes modifications appliquées dans cette mise à jour
* Suppression de la fonction OnMailBoxClick() du langage de script, l'adresse mail faisant maintenant partie de la configuration au même titre que le nom de worker
* Suppression de la possibilité de changer de provider de soft de mining afin de garantir des soft le plus à jour possible avec uniquement le site officiel de Miner Helper comme provider de soft de mining.
* Correction du paramètre d'intensité lorsqu'elle est laissé en automatique
* Correction du redémarrage en boucle de Miner Helper suite à un crash


-- 2.9.2b --

* Correction d'un problème de crash introduit par la 2.9.1b


-- 2.9.1b --

* Le réglage de l'intensité ne sera maintenant activé que si le soft de mining permet la modification de l'intensité


-- 2.9.0b --

* Ajout d'un champs "Intensité" afin de régler facilement l'intensité de minage
* Modification du système de chargement des soft de mining pour l'intensité
* Correction d'un bug empêchant le bon fonctionnement de certain soft de mining lorsque le mot de passe contenait le caractère "@"
* Correction du patcher de Miner Helper qui n'appliquais pas toujours correctement les mise à jour


-- 2.8.2b --

* Optimisation sur le lancement des soft de mining
* Correction d'un bug d'intégration de bminer


-- 2.8.1b --

* Ajout de nouveaux messages de debug pour les logs
* Ajout du protocole cuckaroo29:// (GRIN) à la liste des protocoles
* Correction d'un bug qui faisait que le nom du worker par défaut pouvait être MinerHelperV220b même sur les versions les plus récentes


-- 2.8.0b --

* Maintenant Miner Helper reprendra le minage qui était en cours si un minage était en cours lors de sa mise à jour
* Correction d'un bug pouvant causé un crash lors de la reprise d'un minage après une interruption anormal de Miner Helper


-- 2.7.9b --

* Ajout de la fonction getVersion() au langage de script
* Ajout de la fonction OnProtoBoxClick() au langage de script
* Ajout de la fonction getDay() au langage de script
* Ajout de la fonction getMonth() au langage de script
* Ajout de la fonction getYear() au langage de script
* Ajout de la fonction getHour() au langage de script
* Ajout de la fonction getMinute() au langage de script
* Ajout de la fonction getSecond() au langage de script


-- 2.7.8b --

* Ajout de nouvelles bulles d'aide (tooltip)
* Optimisations du code pour de meilleures performances et une meilleur stabilité
* Correction d'un bug utilisant le mauvais protocole lors du chargement d'un wallet créer sous une version antérieur à Miner Helper 2.7.0b


-- 2.7.7b --

* Correction d'un bug qui collait le nom du worker à l'adresse du wallet


-- 2.7.6b --

* Optimisation de certaines fonctions


-- 2.7.5b --

* Amélioration graphique des boutons du switch rapide qui sont maintenant tous à la même taille et sont correctement organisés peut importe la longueur des noms de wallet


-- 2.7.4b --

* Modification de la fonction startMining() des scripts pour prendre en charge le choix du protocole de pool
* Correction d'un bug affichait plusieurs fois de suite la même chose lors du mining avec bminer
* Correction d'un bug créant un buffer overflow lors du minage avec bminer


-- 2.7.3b --

* Correction de l'affichage de multiple fenêtre demandant de faire la mise à jour de Miner Helper lors de la disponibilité d'une mise à jour


-- 2.7.2b --

* Modification afin de pouvoir prendre en charge plus de soft de mining de différents types


-- 2.7.1b --

* Correction d'un léger bug
* Correction d'un bug qui empêchait le bon fonctionnement de cartains soft de mining


-- 2.7.0b --

* Grosse modification de Miner Helper afin de laisser le choix du protocole de pool à l'utilisateur, ce qui peut être nécessaire sans certains cas
* Modification du template "default" du contrôle à distance suite à la possibilité de choisir le protocole de pool
* Correction d'un bug qui par moment empêchait l'extraction des soft de mining lors de leurs mises à jour


-- Version 2.6.1b --

* Amélioration de la gestion des crashs
* Ajout d'un message en cas de crash afin de prévenir l'utilisateur


-- Version 2.6.0b --

* Ajout d'un contrôle de la présence des fichiers nécessaires au bon fonctionnement de MinerHelper lors du démarrage
* Amélioration de la stabilité de MinerHelper en cas d'erreur non critique
* Correction d'un bug lors de la fermeture de la fenêtre de choix de langue lors du tout premier lancement de MinerHelper


-- Version 2.5.0b --

* Retrait de 2 messages de debug qui ne devait pas être là.


-- Version 2.4.9b --

* Correction de l'affichage du mining en cours sur le contrôle à distance, qui parfois au lieu d'afficher uniquement le wallet, l'affiche avec une partie de son path


-- Version 2.4.8b --

* Ajout d'un menu pour mettre MinerHelper à jour
* Modification du texte de l'option "Vérifier les mises à jour" par "Vérifiers les mises à jour des soft de mining" pour plus de clareté
* Modification du template "default" du contrôle à distane pour ajouter un lien permettant de lancer directement la mise à jour de MinerHelper, et modification de la page d'authentification pour qu'elle soit plus concordante avec les modifications précédentes du template


-- Version 2.4.7b --

* Ajout de la possibilité de mettre MinerHelper à jour depuis le contrôle à distance


-- Version 2.4.6b --

* Correction du bug pouvant faire que MinerHelper tente de se mettre à jour en boucle
* Correction de l'option permettant de ne pas mettre à jour tout de suite


-- Version 2.4.5b --

* Ajout de nouveaux message de debug pour les fichiers de logs
* Légères modifications du template "default" du contrôle à distance
* Maintenant lorsqu'on commence à entrer un nom de miner ou un nom d'algo MinerHelper proposera uniquement les algos ou miners ayant le nom commençant par les première lettres renseignées, cette fonction peut être activer/désactiver via l'onglet configuration (elle est désactivée par défaut)


-- Version 2.4.4b --

* Correction de la liste des plugins


-- Version 2.4.3b --

* Maintenant dès qu'une nouvelle version sera disponible MinerHelper proposera de se mettre à jour
* Correction du scroll de la sortie des miners sur le contrôle à distance


-- Version 2.4.2b --

* Maintenant en cas de crash MinerHelper tentera de se relancer automatiquement
* Maintenant si un minage était en cours la dernière fois que MinerHelper s'est fermer anormalement celui-ci reprendra lors du prochain lancement de MinerHelper


-- Version 2.4.1b --

* Ajout d'une meilleur gestion des crashs afin d'établir des report lors d'un crash
* Maintenant lors de la tentative de fermeture de la fenêtre MinerHelper posera la question si on souhaite réellement quitter l'application ou juste le réduire dans la barre des tâches
* Correction de la possibilité de chargé un plugin qui n'est plus présent dans le répertoire plugins/
* Correction de différents bugs pouvant aléatoirement entraîner le crash de MinerHelper


-- Version 2.4.0b --

* Optimisation du chargement des soft de mining et des algorithmes
* Lors du changement de choix du miner les champs de difficulté et de paramètres additionnels sont maintenant correctement ré-initialisés
* Correction des bugs de chargements de wallet selon si dans la configuration le choix du miner se faisait par algorithme ou non
* Correction du remplissage des sélections des miners et des algorithmes lorsqu'on coche ou décoche l'options "choix du miner selon l'algo"
* Correction d'un bug qui pouvais survenir aléatoirement lors de la création d'un nouveau wallet qui empêchait l'activation de certains champs de saisie


-- Version 2.3.3b --

* Modification de l'arrêt des soft de mining afin de vérifier que le miner est bien arrêté même dans le cas de double processus qu'utilise certain soft.


-- Version 2.3.2b --

* Correction d'un bug entrainant un crash de MinerHelper lorsqu'on essayé de miner à nouveau après qu'un soft de mining se soit arrêté de lui même


-- Version 2.3.1b --

* Ajout d'un menu contextuel sur la sortie des soft de mining, pour pouvoir enregistrer la sortie ou bien l'effacer
* Correction d'un bug lors du chargement d'un wallet qui ne chargeais pas toujours le soft de mining lorsque MinerHelper est configurer pour choisir le miner selon l'algo
* Correction d'un bug sur le switch rapide qui sous certainesconditions indiquait de remplir correctement tous les champs de saisie
* Correction du rechargement des infos des soft de mining après une mise à jour via le menu "Options" => "Vérifier les mises à jour"


-- Version 2.3.0b --

* Amélioration du système de template du contrôle à distance
* Ajout de la gestion de l'erreur 404 du protocole HTTP (fichier introuvable) au contrôle à distance
* Ajout d'une option de configuration pour le template du contrôle à distance
* Ajout d'un rafraichissement automatique toutes les 5 secondes de l'affichage de la sortie des soft de mining sur le contrôle à distance
* Modification du fichier de sortie des des miners pour le contrôle à distance, il s'agit maintenant d'un fichier au format html (afin de permettre la personnalisation, via la classe css "minerlog"
* Correction du bug qui faisait revenir le scroll de la sortie des mineurs en haut lorsqu'on change d'onglet et qu'on reviens sur l'onglet "Mineur"
* Correction du clignotement de la sortie des soft de mining
* Correction du bug qui faisait que l'affiche de la sortie des miners du contrôle à distance, ralentissait le chargement des pages de ce dernier


-- Version 2.2.0b --

* Optimisation du code et amélioration des performances
* Ajout d'un avertissement au lancement d'un soft de mining que celui-ci peut mettre jusqu'à 15 secondes pour démarrer
* Retrait de la fonctionnalité screenshot de MinerHelper depuis le contrôle à distance car devenu inutile depuis la version 2.1.0b
* Meilleur enregistrement de la position de la fenêtre sur l'écran
* Correction d'un bug empêchant la remise à zero des adresses IP authorisées par le contrôle à distance
* Correction du message double d'arrêt du soft de mining
* Correction du bug qui empêchait de savoir que le miner était arrêté car des sorties de miner s'affichait encore à la suite


-- Version 2.1.1b --

* Ajout d'un menu pour les plugins permettant de choisir quels plugins activer et quels plugins ne pas activer
* Ajout de nouveaux messages de debug pour les fichiers de logs
* Correction d'un bug empêchant aléatoirement le lancement des softs de mining


-- Version 2.1.0b --

* Ajout de nouveaux messages de debug pour les fichiers de logs
* Ajout de l'affichage de la sortie des miners sur la page principale du contrôle à distance
* Modification de l'intégration des soft de mining à MinerHelper pour un système plus propre et plus lisible
* Modification du système de skin pour la nouvelle intégration des soft de mining
* Correction du système de skin sur certains onglets
* Correction d'un bug ponctuel sur le parsing du nom du worker
* Correction de bugs sur le parsing des paramètres de configuration des miners
* Correction d'un bug qui empêchait MinerHelper de passé directement à l'onglet "mineur" lorsqu'on click sur le bouton "Commencer à miner"
* Correction d'un bug ponctuel lors de l'arrêt d'un miner qui empêchait celui-ci de s'arrêter
* Correction de l'actualisation du minage en cours sur le contrôle à distance
* Correction d'un bug qui pouvait appeller la fonction OnMinerStopped() des scripts même si le soft de mining n'était pas correctement arrêté
* Correction d'un bug lors de la fermeture de MinerHelper qui tentait parfois de se fermer 2 fois simultanéments


-- Version 2.0.0b --

* Ajout d'un système de plugins qui permettra d'étendre les possibilités de MinerHelper
* Modification du système de chargement de MinerHelper
* Modification du système de chargement des soft de mining
* Optimisation du lancement de MinerHelper (affichage plus plus rapide de la fenêtre principale)
* Optimisation du code de chargements des miners (chargement plus rapide)
* Ajout de la fonction unzip() au langage de script
* Ajout de la possibilité d'activer/désactiver la fonction unzip() pour les scripts
* Amélioration et renforcement de la sécurité du contrôle à distance
* Ajout d'un tooltip sur la case à cocher du contrôle à distance
* Ajout d'un tooltip sur le case à cocher des logs
* Ajout d'un tooltip sur la case à cocher d'activation/désactivation de la fonction unzip() des scripts
* Ajout de la vérification de la définition du login/mot de passe et du port avant de valider l'activation du contrôle à distance
* Correction de l'affichage immédiat des wallets sur le switch rapide lorsqu'ils sont crées depuis le contrôle à distance
* Correction du bug d'enregistrement de l'activation ou non des logs
* Correction d'un léger bug sur les chargements de wallets
* Correction d'un bug d'activation/désactivation aléatoire de certains champs de saisie lors du chargemnet de wallets
* Correction de la fermeture de MinerHelper qui parfois le faisait continué de fonctionner en tâche de fond


-- Version 1.9.9b --

* Ajout de l'affichage de la dernière version disponible
* Ajout des variables %CURRENT_VERISON% et %LAST_VERSION% au système de template
* Ajout de l'affichage des version sur l'index.html du contrôle à distance
* Ajout du lien (clickable) github sous l'affichage de la dernière version disponible
* Ajout de nouveaux messages de logs
* Ajout de multiple contrôles pour éviter les crash de l'applications
* Ré-écriture d'une grande partie du code pour accroître la stabilité
* Correction du chargement de l'activation ou non des logs


-- Version 1.9.8b --

* Correction du parsing des température sur le contrôle à distance
* Correction de la prise de screenshot pour le contrôle à distance


-- Version 1.9.7b --

* Ajout de nouveaux messages de debug pour les fichiers de logs
* Ajout d'une vérification de la présence ou non d'un nom de worker afin d'éviter des problèmes d'adresses sur les pools
* Ajout de la possibilité d'activer/désactiver les logs depuis l'onglet configuration
* Ajout de la possibilité de changer le port du contrôle à distance depuis l'onglet de configuration
* Suppression de l'option "prise de screenshot auto" devenue inutile depuis la version 1.9.5b
* Correction des températures des GPUs qui ne s'affichaient pas correctement
* Correction du bug de mot de passe prédéfini pour le contrôle à distance


-- Version 1.9.6b --

* Ajout de nouveaux messages de debug pour les fichiers de logs
* MinerHelper ne demande plus à être exécuté en adminsitrateur
* Une demande d'ajout d'exception au firewall windows sera affiché lors de l'activation du contrôle à distance pour la première fois
* Correction des crashs intempestifs lorsque le contrôle à distance est activé
* Correction de l'impossibilité de se connecté depuis une autre machine que celle exécutant MinerHelper
* Correction de l'impossibilité de se connecté depuis internet à MinerHelper


-- Version 1.9.5b --

* Ajout de la prise en charge des fichiers BMP par le système de template
* Ajout d'un système de screenshot au contrôle à distance afin de pouvoir voir si le minage se passe correctement (activable/désactivable via l'onglet configration)
* Ajout de nouveaux messages de debug pour les fichiers de logs
* Amélioration de la décompression des mises à jour
* Suppression du fichier 7z.exe devenu inutiles
* Correction du bug de chargement excessif lors de l'accès à des fichiers n'existant pas dans les templates du contrôle à distance


-- Version 1.9.4b --

* Ajout d'un système de log afin d'aider au débugage de MinerHelper
* Correction d'un bug lorsqu'une difficulté avec virgule est indiquée
* Correction d'un bug qui empêchait la fenêtre des soft de mining d'être correctement ancrée à MinerHelper


-- Version 1.9.3b --

* Correction d'un bug sur le chargement des algorithmes pour les soft de mining gérant les 2 types de GPU
* Correction d'un bug qui empêchait certains soft de mining de fonctionner correctement


-- Version 1.9.2b --

* Ajout de la possibilité d'utilisé tout type de fichiers fonctionnant avec HTML pour les templates (fichier image, fichier css, fichier js, etc...)


-- Version 1.9.1b --

* Ajout d'un système de template pour le contrôle à distance
* Ajout d'un système de connexion par login/mot de passe pour le contrôle à distance (le login et le mot de passe se définissent dans l'onglet "configuration")
* Ajout du forward automatique du port 8080 (contrôle à distance) via UPNP/IGD
* Correction de la case à cocher de l'activation du contrôle à distance


-- Version 1.9.0b --

* Ajout de la possibilité de contrôler MinerHelper à distance (activable/désactivable depuis l'onglet de configuration)
* Maintenant MinerHelper demandera les droits administrateur pour être lancer (nécessaire pour le contrôle à distance)


-- Version 1.8.3b --

* Correction d'un bug qui faisait que lors du choix des soft de mining par le choix de l'algorithme, MinerHelper pouvait proposé des soft de mining non compatible avec le type de GPU choisi.


-- Version 1.8.2b --

* Il n'est plus nécessaire de redémarrer MinerHelper pour que de nouveaux skins soient disponible depuis l'onglet "configuration"
* Correction de phrases de traduction buguées/incorrectes
* Correction d'un léger bug sur le système de skin
* Correction d'un bug du type "FILE LOCKED"


-- Version 1.8.1b --

* Le bouton "Arrêter de miner" est maintenant recentrer en fonction de si oui ou non le swith rapide est activé
* Il n'est maintenant plus nécessaire de relancer MinerHelper pour que le changment de skin soit appliqué
* Correction d'un bug qui empêchait d'activer correctement certains champs de saisie pour les soft de mining gérant les GPUs AMD et NVIDIA


-- Version 1.8.0b --

* Ajout d'un message en cas d'échec du téléchargement des soft de mining
* Maintenant lors de la modification du type de GPU la mise à jour se lancera afin de télécharger les soft de mining correspondant au type de GPU
* Les algorithmes sont maintenant classés par ordre alphabétique dans la liste de sélection des algorithmes
* Les soft de mining sont maintenant classés par ordre alphabétique dans la liste de sélection des soft de mining
* Correction d'un bug où les miners NVIDIA se mélangeaient parfois au miner AMD et inversement
* Correction d'un bug en cas de chargement d'un wallet créer pour GPU NVIDIA après changement de config vers AMD et inversement
* Correction d'un bug qui pouvais faire qu'un même algorithme pouvait apparaître plusieurs fois dans la liste de sélection des algorithmes
* Correction d'un bug lié à la non exécution et/ou à la fermeture prématuré du soft de mining
* Correction d'un bug lors du changement de langue via l'onglet "configuration" dans le cas où le nom entré serait erroné
* Correction d'un bug possible lors du change de type de GPU via l'onglet "configuration" dans le cas où le nom du type de GPU aurai été accidentellement modifié
* Corection d'un bug qui empêchait le changement de skin d'être correctement enregistrer dans certains cas


-- Version 1.7.4b --

* Le message concernant la bêta lors de l'accès à l'aide ne s'affichera maintenant que lors du premier accès à l'aide
* Correction de divers bugs liés à l'absence du skin utilisé


-- Version 1.7.3b --

* Ajout de la fonction getLang() renvoyant le nom de fichier de langue utilisé par MinerHelper
* Ajout de la fonction getLangString() permettant de charger un fichier XML et d'y récupérer du texte
* Ajout de la fonction getGPUType() renvoie le type de GPU configurer par l'utilisateur
* Ajout de la fonction formatString() permettant le formatage de chaîne de caractères
* Modification de la fonction startMining() qui peut maintenant prendre en paramètre soit un wallet soit des informations de connexion à un pool de minage
* L'ancienne fonction startMining() est remplacée par la fonction startWallet()
* Ajout de la fonction OnWalletBoxClick() appelée lors du click sur le champs de saisie de l'adresse
* Ajout de la fonction OnPoolBoxClick() appelée lors du click sur le champs de saisie de l'adresse de pool
* Ajout de la fonction OnPortBoxClick() appelée lors du click sur le champs de saisie du port de pool
* Ajout de la fonction OnMailBoxClick() appelée lors du click sur le champs de saisie de l'adresse mail
* Ajout de la fonction OnPassBoxClick() appelée lors du click sur le champs de saisie du mot de passe
* Ajout de la fonction OnAlgoBoxClick() appelée lors du click sur la liste de sélection d'algorithme
* Ajout de la fonction OnMinerBoxClick() appelée lors du click sur la liste de sélection de soft de mining
* Ajout de la fonction OnDiffBoxClick() appelée lors du click sur le champs de saisie de la difficulté
* Ajout de la fonction OnParamBoxClick() appelée lors du click sur le champs de saisie des paramètres additionels
* Correction d'un bug qui empêchait de recharger correctement les scripts


-- Version 1.7.2b --

* Ajout d'une fonction OnSwitch() qui est apellée lors de l'utilisation du switch rapide
* Ajout de la fonction stopMining() qui permet de stopper le mining en cours
* Ajout de la fonction popYesNo() qui permet d'attendre une réponse de l'utilisateur
* Ajout de la fonction popAsk() qui permet aux scripts de demander une info quelconque à l'utilisateur
* Ajout de la fonction OnMinerStarted() qui est appelée dès que le mining est lancé
* Ajout de la fonction OnMinerStopped() qui est appelée dès l'arrêt du mining en cours
* Ajout de la fonction getWalletList() renvoyant la liste de tous les wallets de MinerHelper sous forme de tableau


-- Version 1.7.1b --

* Légère refonte de l'interface de MinerHelper
* Ajout de la possibilité de renseigner un login (nécessaire pour certains pools de minage)
* Ajout de la possibilité d'activer/désactiver le switch rapide
* Le switch rapide se trouve maintenant sur l'onglet "Mineur" pour plus de simplicité d'utilisation
* Ajout de bulles d'aides dans la configuration
* Ajout de la possibilité de ne pas renseigner d'aresse de wallet qui n'est pas nécessaire de communiqué à certain pool de minage utilisant un système de login/password
* Ajout d'un message d'avertissement en cas d'adresse de wallet non communiqué par erreur/oublie
* Correction d'un bug lors de l'annulation des mises à jour automatique


-- Version 1.7.0b --

* Refonte d'une bonne partie de l'interface de MinerHelper ainsi que de ses menus afin de rendre MinerHelper d'avantage intuitif
* Mainenant les soft de mining seront directement affichés dans MinerHelper
* Ajout d'un boutton "Arrêter de miner" pour arrêter le soft de mining en cours
* Intégration de l'aide directement accèssible depuis MinerHelper


-- Version 1.6.0b --

* Ajout d'un système de skin permettant de modifier (un peu) l'apparence de MinerHelper
* Maintenant lors du click sur le bouton "Commencer à miner" si un soft de mining était déjà en cours d'exécution il sera stoper avant d'en lancer un autre.
* Maintenant lorsque le switch rapide est activé il sera désactivé lors du click sur "Nouveau wallet" ou "Charger un wallet"
* Il est maintenant possible d'ajouter l'adresse du pool accompagné du port dans le champs adresse du pool, MinerHelper déplacera le numéro de port automatiquement dans le champs port
* Ajout de bulles d'aides lorsqu'on passe la souris aux dessus des différents champs de saisie
* Maintenant lors de la fermeture de la fenêtre de téléchargement des mises à jour par l'utilisateur un message demandant confirmation s'affichera
* Correction d'un bug qui empêchait de choisir le programme de minage lors de l'inversion du choix entre choix du soft de mining par algorithme ou choix direct du soft de mining
* Correction du bug "FILE LOCKED" lors du choix du type de carte graphique
* Correction d'un bug qui empêchait par moment de passer les paramètres additionles aux soft de mining


-- Version 1.5.4b --

* Correction d'un bug qui lors du changement d'un soft de mining faisait que les algos du soft précédent était conservé dans la liste d'algorithme


-- Version 1.5.3b --

* Ajout d'un menu configuration (Fichier => Configuration)
* Ajout de la possibilité de changer de langue via le menu Configuration
* Ajout de la possibilité de changer de type de GPUs via le menu Configuration
* Ajout de la possibilité d'activer/désactiver les mises à jour automatique via le menu Configuration
* Ajout de la possibilité d'activer/désactiver la fonction download() pour les scripts, via le menu Configuration
* Correction d'un bug qui empêchait de changer de soft de mining lorsqu'on chargeait un wallet utilisant un soft de mining avec choix d'algorithme
* Correction d'un bug lors du re-chargement de la liste des soft de mining


-- Version 1.5.2b --

* Ajout de la fonction download() au langage de script de MinerHelper (désactivé par défaut) (Note: Les scripts ne peuvent télécharger que dans le répertoire scripts/)
* Ajout de la possibilité d'activer ou de désactiver la fonction download() du langage de script via le fichier MinerHelper.ini (désactiver par défaut)
* Correction d'un bug mineur qui pouvait empêcher la sauvegarde correct du fichier MierHelper.ini lors de la femerture de MinerHelper pendant certaines actions
* Correction d'un bug qui empêchait de prendre en compte les scripts nouvellement ajoutés
* Correction de la fenêtre de téléchargement de mise à jour qui avait gardée la possibilité d'être agrandie
* Correction de la fenêtre de séleection des scripts qui avait gardée la possibilité d'être agrandie


-- Version 1.5.1b --

* Ajout d'une gestion partielle des erreurs des scripts afin de ne pas empêcher MinerHelper de fonctionner même si un script contiens des erreur
* Ajout de l'indication si un script ne contient pas les 2 fonctions OnLoad() et OnLoop()
* Ajout de la possibilité d'activer ou désactiver certains scripts
* Ajout d'un menu "Scripts" avec les sous menus "Recharger les cripts" et "Choisir les scripts actif"
* Ajout de la fonction getLoopInterval() au langage de script, cette fonction renvoie l'interval actuel auquel est appelé la fonction OnLoop()
* Ajout des textes concernant les scripts et le menu Scripts au système multilingue et fichier fr.xml


-- Version 1.5.0b --

* Ajout de l'intégration de script LUA avec fonctions propres à MinerHelper afin de pouvoir automatiser certaines actions.
* Maintenant le choix des soft de mining est par défaut effectué via le choix de l'algo, ce qui est plus simple pour les débutants ne connaissant pas nécessairement les noms des soft
* Ajout de la sauvegarde automatique des adresses de pool déjà entrées afin de pouvoir les sélectionner plus tard sans avoir besoin de ré-écrire les adresses.
* Ajout du même principe pour les adresses mails 
* Ajout de la possibilité de désactiver les mises à jour automatique des softs de mining (via le fichier MinerHelper.ini)


-- Version 1.4.5b --

* Les options on été scindées en 2: "options" et "options avancées" et "options avancées" est maintenant un sous menu du menu "Options"
* Ajout d'une option pour choisir le programme de minage selon l'algorithme
* Ajout de la vérification de la présence du soft de mining avant de son exécution


-- Version 1.4.4b --

* Correction du bug qui listait [ALGOBOX] comme algorithme de minage


-- Version 1.4.3b --

* Ajout de la vérification de l'url de téléchargement avant de commencer le téléchargemnet d'un soft de mining
* Ajout d'une option de vérification des mises à jour
* Ajout d'une option pour changer de provider de soft de mining
* Correction de l'icone de la fenêtre des téléchargements de mises à jour


-- Version 1.4.2b --

* Maintenant seul les soft de mining compatible avec le GPU choisi seront installé et mis à jour
* Ajout des textes des mise à jour au système multilingue


-- Version 1.4.1b --

* Ajout de la mise à jour automatique des soft de mining fournis avec MinerHelper
* Modification du système pour les soft de mining pour les mise à jours automatique


-- Version 1.4.0b --

* Nouveau système pour les soft de mining pour simplifier l'ajout de futur soft de mining et permettra aux utilisateurs d'ajouter eux même les soft de mining qu'ils souhaitent
* Ajout des textes manquants au système multilingue
* Correction d'un bug lors du chargement des informations
* Correction du nom du worker actuel dans la fenêtre de changement de nom du worker


-- Version 1.3.1b --

* Ajout de la possibilité de réduire MinerHelper dans la barre des notifications Windows
* Ajout d'un champs de saisie mot de passe (facultatif)
* Le champs de saisie de l'adresse mail est maintenant facultatif


-- Version 1.3.0b --

* Ajout de la possibilité de renommer le worker
* Ajout d'un accès rapide d'un coup d'oeil aux wallets avec début de mining automatique
* MinerHelper possède maintenant la possibilité d'être multilingue (voir lang/fr.xml)


-- Version 1.2.6b --

* Ajout de Phoenix Miner (miner ethash) AMD+NVIDIA
* Ajout de la désactivation des leds des GPUs par défaut avec ccminer
* Ajout de la température limite pour ethminer
* Ajout de la possibilité de miner avec GPU AMD et NVIDIA ensemble
* Blockage des devfees de Claymore
* Blockage des devfees de ZMiner
* Blockage des devfees de BMiner


-- Version 1.2.5b --

* Correction d'un important bug sur le chargement des wallets


-- Version 1.2.4b --

* Correction du champs de saisie des paramètres additionels qui ne s'activais pas toujours
* Modification de la police et de la taille de caractères
* Il n'est maintenant plus possible de lancer plusieurs instances simultanées de MinerHelper


-- Version 1.2.3b --

* Correction de l'activation du choix des algorithme pour les soft de mining
* Correction de l'affichage des algos lors du chargmenet d'un wallet
* Ajout du miner Z-Enemy (NVIDIA)


-- Version 1.2.2b --

* Lors de la création d'un nouveau wallet le champs de saisie de difficulté est maintenant correctement effacé
* Lors du changement de soft de mining le champs de saisie de difficulté est maintenant correctement effacé
* Lors du chargement d'un wallet les champs de saisie non utiles sont maintenant correctement désactivés
* La température limite (65°C par défaut) peut maintenant être modifier via le fichier MinerHelper.ini


-- Version 1.2.1b --

* Correction du bug qui empêchait de lancer le mining
* Correction du bug qui empêchait l'enregistrement des infos de mining
* Correction pour l'utilisation de Claymore


-- Version 1.2.0b --

* La difficulté est maintenant correctement enregistrée
* Ajout du choix du type de carte graphique au premier lancement
* Ré-organisation des soft de mining
* Mise à jour des soft de mining
* Ajout de sgminer (AMD)
* Ajout de XML-Stak (AMD+NVIDIA)
* Les soft de mining sont maintenant proposés selon le type de GPU utilisé
* La position de la fenêtre est maintenant sauvegardée
* Le champs de saisie des paramètres additionnels est maintenant disponible seulement si possible
* Correction de l'icône manquante de l'application dans la barre des tâches


-- Version 1.0.1b --

* La température maximum des GPUs sous Claymore,CCMiner,BMiner,ZMiner et Ewbf's miner est maintenant fixée à 65°C par défaut
* Ajout de l'option --color de zminer par défaut
* Ajout de la possibilité de définir la difficulté de minage pour ccminer
* Toutes les options par défaut ne sont plus utilisées lors de l'utilisation des paramètres avancés !
* Correction du bug de sauvegarde d'un nouveau wallet par dessus le wallet précédent
* Suppression du popup lors du click sur le bouton "Commencer à miner"


-- Version 1.0.0b --

* Initial release
