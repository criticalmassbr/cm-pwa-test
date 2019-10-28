# Critical Mass PWA Test

## How to run

```console
  yarn
  yarn start

```

## Objetivo

Desenvolver uma aplicação para consultar álbuns de um determinado artista

## Stack

- React
- styled-components
  - CSS Grid
- MobX
- [API GraphQL Spotify](<https://spotify-graphql-server.herokuapp.com/graphql?query=%7B%0A%20%20queryArtists(byName%3A%20%22Metallica%22)%20%7B%0A%20%20%20%20name%0A%20%20%20%20id%0A%20%20%20%20image%0A%20%20%20%20albums%20%7B%0A%20%20%20%20%20%20name%0A%20%20%20%20%20%20id%0A%20%20%20%20%20%20image%20%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%0A>)
  - Para simplificar o App, considere o primeiro item do array de `queryArtists`
- Service Worker
  - App deve funcionar off-line

## Wireframes

### Desktop Browser

![web](./docs/browser01.png)

### Mobile Browser

![mobo](./docs/mobo01.png)

## Pull Request

Submeter uma PR [para esse repositório](https://github.com/criticalmassbr/cm-pwa-test) com o README atualizado sobre como executar o projeto.
