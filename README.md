# next-ssr-markdown
A demo for edit &amp; priview markdown bases on next-ssr quickly! See: https://guopingxiao.github.io/next-ssr-markdown

## Features
 - next.js
 - simplemde-markdown-editor
 - react-markdown

## Depoly by pm2

```bash
# 1. install pm2
$ npm install -g pm2

# 2. build project
$ yarn build

# 3. pm2 deploy project
$ pm2 start pm2.config.js --env production
```

## Demo Image
 - home page
  ![](https://user-gold-cdn.xitu.io/2019/2/25/169203f9e7cad512?w=2348&h=1040&f=png&s=1586684)
 
 - normal editor
  ![](https://user-gold-cdn.xitu.io/2019/2/25/169203ff351e6fd5?w=1228&h=1198&f=png&s=517734)
 
 - side-by-side editor
  ![](https://user-gold-cdn.xitu.io/2019/2/25/16920404565fb5db?w=2292&h=792&f=png&s=134608)
 
 - preview markdown
  ![](https://user-gold-cdn.xitu.io/2019/2/25/16920406f5cbca8f?w=2046&h=850&f=png&s=160736)
