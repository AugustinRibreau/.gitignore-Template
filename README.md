# .gitignore 
`.gitignore` spécifie les fichiers à ignorer. Git considère chaque fichier de votre copie de travail comme appartenant à l'un des trois <br/> types suivants :

<b>tracké</b> : un fichier qui a été stagé ou commité au préalable ; <br />
<b>non tracké</b> : un fichier qui n'a pas été stagé ou commité ; <br />
<b>ignoré</b> : un fichier que Git a explicitement reçu pour instruction d'ignorer. <br />
<br />
Les fichiers ignorés sont généralement des artefacts de build et des fichiers générés par la machine qui sont dérivés de votre dépôt source ou qui ne devraient pas être commités. Quelques exemples fréquents : <br />

- caches de dépendance, comme le contenu de /node_modules ou /packages
- le code compilé, comme les fichiers .o, .pyc et .class ;
- les répertoires de sortie de build, comme /bin, /out ou /target ;
- les fichiers générés lors de l'exécution, comme .log, .lock ou .tmp ;
- les fichiers système cachés, comme .DS_Store ou Thumbs.db ;
- fichiers de configuration IDE personnels, comme .idea/workspace.xml

Les fichiers ignorés sont trackés dans un fichier spécial appelé `.gitignore` qui est enregistré à la racine de votre répertoire. Il n'existe pas de commande Git ignore explicite : à la place, le fichier `.gitignore` doit être édité et commité manuellement lorsque vous souhaitez ignorer de nouveaux fichiers. Les fichiers `.gitignore` contiennent des modèles mis en correspondance avec les noms des fichiers de votre dépôt pour déterminer s'ils doivent ou non être ignorés.

https://fr.atlassian.com/git/tutorials/saving-changes/gitignore
  
