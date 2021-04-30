# HAproxy

Ce projet permet de tester le fonctionnement d'un load balancer.Il utilise HAproxy et sa fonction de roundrobin.
On accède aux conteneurs herbergeant le service web sur le port 8080. 
Depuis la machine hôte sur `localhost:8080`, et depuis internet via `ipPublicHost:8080`.

![gnome-shell-screenshot-BTJ810](https://user-images.githubusercontent.com/44028461/116010655-a1e16680-a620-11eb-859e-0ac21f3901d4.png)

## Lancer le load balancer avec les dernières images disponibles
```
docker-compose pull && docker-compose up
```
