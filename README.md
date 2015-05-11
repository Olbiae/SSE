# SSE
Projet Sécurité des Systèmes Embarqués

Attaques timings contre les caches des CPU

L'utilisation des caches des CPU permet d'accélérer grandement l'exécution des
programmes. Néanmoins, elle introduit une grande disparité des temps d'accès à
une donnée en fonction de si elle présente dans le cache ou non. Cette
différence peut être exploitée pour monter une attaque SCA (timing attack). Des
chercheurs ont montré qu'il était ainsi possible pour une application de voler
du matériel cryptographique manipulé par une autre application (y compris dans
une autre machine virtuelle). Cette étude portera sur une présentation du
fonctionnement de ces attaques timings contre les caches, ce qu'elles permettent
de faire et les contre-mesures pour se protéger de contre ces attaques.
