# Docker

## Inledning

Tanken med labben var att labba med tekniker som är "buzzwords" i branschen.

## Utförande

* Installation av docker på Linux Fedora baserad dator.
[Docker docs](https://docs.docker.com/engine/install/fedora/)

* Skapa och köra en nginx container med hjälp av dockerfile

* Få upp en container med något visuellt

* Bygg en egen image med hjälp av docker compose.yaml

* Skapa en ny container med en databas

* Skapa en fil som skickas till container, *init.sql*

## Lärdommar

* `docker compose down -v` - rensar en befintlig image

* Lägg till `volume` i *compose.yaml* för att skapa flera databaser från start via *init.sql*

## Kommandon

* `docker images` lista images

* `docker run` starta en container

* `docker ps` visa körande containrar

* `docker stop` stoppa en container

* `docker rm` tar bort en container

* `docker rmi` tar bort en image

* `docker system prune` rensa oanvända resurser

