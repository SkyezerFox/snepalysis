# snepalysis

COVID-19 analysis API using JHU data.

## Scripts

### yarn lint

- Runs the linter on all files in the `src` directory.

### yarn build

- Compiles the source TypeScript code, and lints the source.

```bash
$ tsc --project ./ && eslint ./src/**/*.*
# Some lovely linting output
# ...
# Done in 5s
```

### yarn build:watch

- Starts the TypeScript compiler in watch mode.
