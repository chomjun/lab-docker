##Lab8-swarm:
# docker swarm init --advertise-addr 192.168.0.38
# docker swarm join-token manager
# docker swarm join-token worker

# docker node ls
# docker service create --name lab8-01 -p 2080:80 --replicas 1 nginx:alpine
# docker service ls
# curl -si 192.168.0.38:2080
# curl -si 192.168.0.39:2080
# docker service scale lab8-01=3
# docker service ps lab8-01
# docker service inspect lab8-01
