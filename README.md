# Installation
```npm i syn-generate-ids```

# Usage (all parameters are optional)
```ng g syn-generate-ids:generate-ids --prefix=settings-feature-ids --path=src/app/modules/layout --elements=h1,p```



### Publish with private namespace
```npm --no-git-tag-version version minor```

```npm publish --access=public```

```npm init --scope=synergy```


# Getting Started With Schematics

This repository is a basic Schematic implementation that serves as a starting point to create and publish Schematics to NPM.

### Testing

To test locally, install `@angular-devkit/schematics-cli` globally and use the `schematics` command line tool. That tool acts the same as the `generate` command of the Angular CLI, but also has a debug mode.

Check the documentation with

```bash
schematics --help
```

### Unit Testing

`npm run test` will run the unit tests, using Jasmine as a runner and test framework.

### Publishing

To publish, simply do:

```bash
npm run build
npm publish
```

That's it!
