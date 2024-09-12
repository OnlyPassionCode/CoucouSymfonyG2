# Coucou

Dans le `.env.local` on met le chemin vers la DB :

```env
DATABASE_URL="mysql://root:@127.0.0.1:3306/coucousymfonyg2?serverVersion=8.0.31&charset=utf8mb4"
```

Après la création de la database en `MySQL` nommée `coucousymfonyg2` via la commande :

```env
symfony console d:d:c
```

Nous allons créer des entités.