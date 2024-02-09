Local dev

```
nvm use 18
npm i --legacy-peer-deps
```

Run using Angular CLI
```ng g generate-ids:generate-ids --prefix=settings-feature-ids --path=src/app/modules/layout```

Dev run:

```schematics .:generate-ids --dry-run=false --prefix=settings-feature-ids --path=src/app/nested-html/nested-html-level-2```
```schematics .:generate-ids --dry-run=false --prefix=settings-feature-ids --path=src/app/nested-html/broken```

Existing docs
https://synergysuite.atlassian.net/wiki/spaces/UTF/pages/1142849562/Generating+ids+inside+web-ui
https://synergysuite.atlassian.net/wiki/spaces/UTF/pages/1122500615/uniqueStrId

How to install and run on an actual Angular project

Run from local directory
schematics /Users/anton/git/ng-web/generate-ids/src/collection.json:generate-ids --dry-run=false --prefix=settings-feature-ids --project ng-web

npm i git+https://github.com/antonnikprelaj/test-id-generator-angular-schematic.git --legacy-peer-deps

npm i git+https://github.com/antonnikprelaj/test-id-generator-angular-schematic.git --legacy-peer-deps

TODO: Generate code with WebStorm



Guide: https://dzone.com/articles/create-your-first-angular-schematics

Create a new one
schematics schematic --name demo


Root source directory

```npm run build``` or auto compile ```npm run build -- --watch```


```schematics .:generate-ids --prefix=settings-feature```

```schematics .:generate-ids --dry-run=false --prefix=settings-feature-ids```




## Templates

mkdir -p src/generate-ids/files/src/app

cd src/generate-ids/files/src/app
touch app.component.ts
touch app.component.html

