# getignore

Command line utility for grabbing .gitignores from github.com/github/gitignore

## Usage

Navigate to somewhere on your `$PATH` and run

```bash
curl -o getignore -sSL https://raw.githubusercontent.com/brymck/getignore/master/getignore
chmod +x getignore
```

You can then run

```bash
./getignore
```

to see available templates, and something like

```bash
getignore Python
```

to create a new `.gitignore` in the current directory that's a copy of [`Python.gitignore`](https://github.com/github/gitignore/blob/master/Python.gitignore).
