Dans ce laboratoire 2, nous avons appris à déployer une application web simple développée avec Flask
et à l'exposer derrière Nginx. Nous avons configurer Nginx pour distribuer les requêtes entre deux
instances de l'application, testant ainsi la tolérance aux pannes et la gestion des volumes de 
requêtes. Nous avons également partagé et modifié le code via GitHub.

Réponses aux questions:
6 - Quand on arrête l'application Python, la page web n'est plus accessible via l'adresse 
http://IP_DE_LA_MACHINE:3001/

16 - En faisant un refresh plusieurs fois, nous remarquons que les réponses alternent entre les
deux applications, indiquant que Nginx distribue les requêtes entre les deux machines.

17 - a. Quand on arrête l'application, elle est toujours accessible via l'adresse
http://IP_DE_LA_MACHINE:3001/
     b.   Quand on arrête l'application, elle n'est plus accessible via l'adresse
http://IP_DE_LA_MACHINE:8181/

Pour finir, voici un lien panopto pour la vidéo de démonstration du laboratoire:
https://uqac.ca.panopto.com/Panopto/Pages/Viewer.aspx?id=81c06e66-3934-4b77-bba3-b1fd0002930c
