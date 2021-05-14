<h1 align="center">
  package-env-example
</h1>

<p align="center">
  Good and bad examples of using environment variables in <code>package.json</code>
</p>

```bash
$ pnpm -s bad1
'NODE_ENV' is not recognized as an internal or external command,
operable program or batch file.
```

```bash
$ pnpm -s good1
{ NODE_ENV: 'production' }
```

```bash
$ pnpm -s good2
{ NODE_ENV: 'production' }
```

```bash
$ pnpm -s good3
{ NODE_ENV: 'production' }
```
