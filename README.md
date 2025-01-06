# Headers API

Cette application est une API simple développée en TypeScript avec le module natif http de Node.js. 

Elle expose un endpoint `/ping` qui retourne les headers de la requête HTTP au format JSON lorsqu'une requête GET est effectuée. Toute autre requête retourne une réponse vide avec un code HTTP 404.

## Prérequis

- `Node.js`
- `npm`
- `TypeScript`

## Usage

```console
$ git clone https://github.com/geoffrey-diederichs/WIK-DPS-TP01.git

$ cd WIK-DPS-TP01/

$ ./run.sh
```

Pour spécifier un port au choix :

```console
$ export PING_LISTEN_PORT=9090

$ ./run.sh
```