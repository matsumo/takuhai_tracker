# 宅配トラッカーを Docker でサクッと動かすやつ

## build front

(必要なのは、 `public/css/*.css` と `public.js/*.js` )

```sh
$ npm install
$ npm run production
```

## build docker image
```sh
$ docker compose build
```

## run docker image
```sh
$ docker compose up -d
```

## stop docker image
```sh
$ docker compose down
```
