# Microservice-projet

Groupe 7 : Mathis OUDJANE, Jules DUARTES, Mody DIAKHITE, Minh-Quang HOANG, Callicles BAZOLO

### Setup project : 

- Créer un .env à la racine du projet avec les variables d'environnement Java et Python : 

```properties
SPRING_DATA_MONGODB_URI=lien vers la db mongo distante
MONGO_URI=lien vers la db mongo distante
```


ajouter un .env à la racine de Microservice_order
```properties
MONGO_URI=lien vers la db mongo distante
```

ajouter un .env à la racine de Microservice review
```properties
MONGO_URI=lien vers la db mongo distante
```

ajouter un .env à la racine de Microservice user
```properties
MONGO_URI=lien vers la db mongo distante
PORT=4000
JWT_SECRET=le jwt
```


- Lancer le projet avec la commande suivante : 

```shell
docker compose up
```

Lien vers les différentes endpoints :
- http://localhost/dashboard/

Microservice poduct : http://localhost/product/swagger-ui/index.html
Review : http://localhost/product/swagger-ui/index.html
