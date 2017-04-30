# mvn_servlet_demo

Salut :-)

C'est un petit projet pour s'initier à l'environnement J2EE 
en utilisant Maven quasi-exclusivement (sans utiliser Netbeans ou Eclipse).

Pour commencer il faut extraire l'archive "calculatrice" dans un dossier portant de preference,
le même nom puis lancer le script install.bat qui va executer la command "mvn install"...
Par la suite il faut aller à l'URL de deploiment de Tomcat (le webmanager) en lançant le raccourci 
url de deploiement (fourni) ...une fois l'interface du webmanager en nmarche,on peut deployer l'application 
en donnant le chemin du fichier .war (situé dans le dossier target du projet maven).
Voila,il ne reste que de tester la calculatrice avec quelques operations de calcul simple.
l'application ne demande comme dependances externes que la bibliotheque JSTL pour formater les dates  
(donc il faut disposer d'une connexion internet ...)
les autres bibliotheques de base(comme les Servlets) sont fournies par default par Tomcat,
qui est un conteneur leger pour les Servles.

quelques captures d'ecrans sont fournies(dossier captures)... 
Je reste à votre écoute pour toutes interrogations.

amicalement,

jihed
 
