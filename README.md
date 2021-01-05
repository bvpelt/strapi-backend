# Strapi application

A quick description of your strapi application

## References
https://strapi.io/documentation/v3.x/getting-started/quick-start.html

## Upgrade
van 3.3.1 -> 3.4.1
- aanpassen package.json 
    - vervang strapi* 3.3.1 naar 3.4.1
- update knex -> 0.21.15
- remove build .cache .tmp directories
```bash
$ rm -Rf build .cache .tmp
```
- restart strapi-backend
```bash
$ npm run develop
```

Add data again

