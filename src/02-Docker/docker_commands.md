# Runing Docker Compose

```sh
docker-compose up -d mongodb
```

In Linux:

```sh
sudo docker-compose up -d mongodb
```

# Is the image runing?

```
docker-compose ps
```

# Execute the terminal

```sh
docker-compose exec mongodb bash
```

# Connect with mongosh

```sh
mongosh "database:string"
```

# Mongosh Commands

```sh
show dbs
show collections
```