[![Build Status](https://travis-ci.com/iGOEGGO/diplomprojekt.svg?token=sHpQspLqymz32HoPUpxz&branch=master)](https://travis-ci.com/iGOEGGO/diplomprojekt)
[![CircleCI](https://circleci.com/gh/iGOEGGO/diplomprojekt.svg?style=svg&circle-token=18fc40d226ea9298fae8cc29e037758c09e71c1e)](https://app.circleci.com/pipelines/github/iGOEGGO/diplomprojekt)

# dipl

## Umsetzung 



## Deployment 

### Lokales Deployment

Ein lokales Deployment der Software ist durch folgende Befehlsabfolge möglich: 

```shell
cd docker_tdegold
docker-compose up -d
```



### Cloud-Deployment 

#### Heroku

Ein Deployment der Software über Heroku ist denkbar einfach, nachdem hierfür das entsprechende Dockerfile verwendet werden kann: 

```shell
cd docker_tdegold
heroku login
heroku create <app-name>
heroku container:push web --app <app-name>
heroku container:release web --app <app-name>
```



## Team

Teammitglieder

@jborensky-tgm, @tdegold-tgm, @chaslinger-tgm, @dzimmermann-tgm