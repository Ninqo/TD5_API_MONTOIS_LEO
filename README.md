# INSTALLATION DE L'API

## Utilisation

### Prérequis
1. Pour faire fonctionner cette API il faut d'abord installer : 
   * Node.js
   * npm

2. Ensuite initialiser un fichier node.js :  
   *"npm init -y"* dans l'invite de commande


### Présentation
Cette API permet de créer, modifié ou supprimer une liste d'utilisateur. Avec cette liste d'utilisateur on y ajoute l'email correspondant à  cet utilisateur.


### Composition 
L'API est composé d'un dossier *src*, de plusieurs fichier **json** (*nodemon.json*, *package.json*, *tsconfig.json*) et d'un fichier en **.env**

Dans le dossier src on retrouve deux autres dossiers : 
* *controllers*
* *routes*
Et on retrouve également un fichier nommé *index.ts*

Dans le fichier *controllers* on retrouve un fichier **ts** nommé *user.contoller.ts*.

Dans le fichier *routes* on retrouve un fichier **ts** nommé *user.routes.ts*.

### Fonctionnement

<img width="873" height="737" alt="image" src="https://github.com/user-attachments/assets/cc94be34-c040-4b86-a407-392618542918" />


Sur cette capture d'écran on peut voir que lorsque l'on fait une requête de type *get* avec l'adresse 4000 on reçoit une réponse avec un affichage de liste d'utilisateur.

<img width="902" height="746" alt="image" src="https://github.com/user-attachments/assets/5e603e37-584f-4527-91a1-3099eabe62cf" />


Maintenant on rajoute un nouvel utilisateur avec la requête *post* ici on rajoute l'utilisateur du nom d'alice et son adresse email.

<img width="876" height="846" alt="image" src="https://github.com/user-attachments/assets/0214faac-6faa-4dd1-811a-fa9758b28c19" />


Voila le résultat obtenu maintenant avec la requete *get*.
