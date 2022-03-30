## Description

* Ping Pong service backend Framework repository.

* This service is communication application for parent, student, home schooling teacher!

* programming & design specification is located in [here](https://www.notion.so/DND-6-_Team4-7456d5e50713440ab86fa867f5dee453).

* The notion page is work only the time I want to. if you want to know something, please email me!!


## Installation
- Framework : Nest JS (한국어 공식문서 : [https://docs.nestjs.kr](https://docs.nestjs.kr/))
- Runtime Env : Node(14.17.x)
- Package Manager : npm 8.4.1
- CI/CI : Git, Github

### use package.json
```bash
$ npm install 
```

### use package-lock.json
```bash
$ npm ci
```
## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Docker
```bash
$ docker-compose -f docker-compose.yml up

$ docker ps // work container

$ docker rmi $(docker ps -q) // remove docker image
```

## Test

```bash
# unit tests
$ npm run test
$ npm run test -- {xxx.test.ts} // check only a file

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

### DND ACADEMY

- [visit github organization](https://github.com/dnd-side-project)
- thank you for supporting us!!

### Nest Framework
Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [shwan lee](https://github.com/LeeSeunghwanSeungLee)


