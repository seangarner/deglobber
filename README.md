# deglobber
> list files using globs respecting excludes from .gitignore

## install
```
npm install -g deglobber
```

## use
```
  USEAGE
    $ deglobber [GLOB]

   List files matching globs respecting ignore syntax from .gitignore

  OPTIONS
    -i, --ignore-file=FILE  Load .gitignore syntax patterns from file (DEFAULT: .gitignore)
         --no-ignore-file    Don't read patterns from file (requires --ignore)
         --ignore=RULE       Additional ignore pattern

  EXAMPLES
    $ deglobber '**.js'

     Find all javascript files excluding those matched by .gitignore

     $ deglobber --ignore-file .npmignore

     Find all files not excluded by .npmignore
```
