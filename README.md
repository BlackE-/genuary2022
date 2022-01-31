# genuary2022

1. We need to create a new npm project
```
npm init
```

(say yes to everything)

2. Install gh-pages

```
npm i gh-pages --save-dev
```

3. Add a new npm script
```
"deploy": "gh-pages -d ."
```

4. Deploy!
```
npm run deploy
```