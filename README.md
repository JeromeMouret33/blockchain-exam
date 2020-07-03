Plateformes Blockchain et Cryptographie
=======================================


Question1
---------

De base la blockchain est sécurisée de par le fait que son utilisation est mise en place pour échanger des données entre plusieurs entités qui ne se font pas confiance. Chacune de ces étapes sont cryptographiées ce qui permet la sécurisation des données et des transactions. A contrario, un système standard demandera la mise en place d"une gestion utilisateurs dependante de la technologie utilisée. 



Question2
---------

Son effondrement brutal est survenu en février 2014, et serait dû à un piratage informatique. Les pirates auraient en effet réussi à détourner 744 408 bitcoins correspondant à des transactions refusées à tort, sans que la manœuvre informatique soit détectée par une réconciliation quotidienne des opérations par Mt. Gox. Il est dit que ce serait des employés de la socièté qui seraient responsables du hack !

Comme dans toute strucure, il est neccessaire d'effectuer des audits en interne pour avoir une vision d'enssemble sur les activitées en interne. Le but étant de ségmenter un maximum les droits donnés au employés sur les différentes couches de la plateforme d'échange de bitcoin. De plus, mettre en place un service sécurité composé d'une équipe SOC et pentest aurais pu rendre la démarche proactive.

La solution est les « hardware wallets », portefeuilles matériel, protègent vos fonds de façon optimale et permettent, avec un bon niveau de sécurité, l’envoi et la réception de bitcoins depuis n’importe quel appareil, même compromis.


Question3
---------

Le smart contract est la solution, c'est un contrat intelligent est un accord entre plusieurs parties sous forme de code informatique.
Ils sont distribués et de ce fait, stockés dans une base de données publique et ne peuvent pas être modifiés (dans notre cas une blockchain).
Ils permettent d’effectuer des transactions de manière automatique sans avoir recours à une tierce partie, ne dépendant ainsi de personne. 
Les transactions automatisées se produisent lorsqu’une ou plusieurs conditions du contrat sont remplies. 


Question4
---------

La blochain est publique, il n'y a aucun interet à chiffrer les flux. Même si les flux etaient altérés, la blochain en s'en verait pas impactée. le seule cas utile et celui ou votre blockchain ne devrait pas être pubilque, dans ce cas un chifrement "end to end" serait neccessaire. 


Question5
---------

En effet perdre ses clés c'est perdre ses fonds, trés mauvaise idée de se tatouer ses clés sur le bras !! Préférez un cold wallet ! Ce stockage à froid a la particularité de stocker la clé privée hors ligne. À l’abri des attaques malveillantes, il peut prendre la forme d’un portefeuille papier (paper wallet) ou d’un portefeuille matériel comme un disque dur externe ou une clé USB.


Question6
---------

Il faut immédiatement mettre ce papier à l'abrit et avertir le personnes concernées ! Cette phrase permet la recupération de wallet !


Question7
---------

La cryptographie asymétrique peut être illustrée avec l'exemple du chiffrement à clef publique et privée, qui est une technique de chiffrement, c'est-à-dire que le but est de garantir la confidentialité d'une donnée avec le même principe d'échange de clés que le "handshake" utilisé pas le protocole HTTPS. L'algo de chiffrement le plus pertinent est le SHA 256.


Question8
---------

Les signatures numériques, en plus d’assurer l’intégrité, permettent de  vérifier l’origine de l’information  et son authenticité.


Question9
---------

Les fonctions de hachage – notamment SHA-256 pour ce qui concerne Bitcoin – sont des fonctions mathématiques qui permettent de transformer une chaine de caractères de longueur indifférente en une autre chaine de longueur fixe


Question10
----------

Il est similaire à Base64 mais a été modifié pour éviter à la fois les caractères non alphanumériques et les lettres qui pourraient sembler ambigus lors de l'impression.


Question11
----------

La blockchain privée son lot d'avantage téls que la gouvernance simplifiée, acteurs connus, coûts réduits, rapidité, confidentialité. Le tout sans la perte de contrôle qu’impliquait la version publique issue du Bitcoin.


Question12
----------

Turing Complete :  Langages permettant l'implémentation de variables. C, C++, java etc...
Non Turing complete : Pas de variables. Langages dédiés au traitement de problèmes spécifiques


Question13
----------

Remplacer le token ERC721 par un ERC1400, il a pour but de définir un standard pour les securities token. Il va falloir être  vigilent sur sa compatibilité avec les différents tocken. Ce type de token sera compatible avec les tokens ERC-20 et ERC-777.


Question14
----------

Faire attention au montant minimum définit dans le smart contract


Question15
----------

Il faut que le contrat soit rempli pour pourvoir récuprer les fonds assiciés. Après qu’une transaction a été effectuée, elle ne peut —théoriquement— pas être renversée.


Question16
----------

Overkill ! Un système decentralisé n'est utile que si plusieurs partis d'un projet ne font pas confience. Un simple DB est suffisante.


Question17
----------

Il existe certain framework capable de deployer le front directement sur les clients. Ex : Truffle vs Embark


Question18
----------

Une fois qu'un contrat est créé sur la blockchain, il ne peut pas être modifié. Si vous devez modifier votre code, vous devez déployer une nouvelle version de votre contrat intelligent.
