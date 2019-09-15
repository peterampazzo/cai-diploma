# generate-diploma

Time saving script. Given a list of names and a certificate template it generates a copy for each candidate.

## Usage

Installation: `yarn install`, then you can run:

```
node app.js -l [list]
```

The folder structure follow the group name (e.g. `example`):

```
generate-diploma/
│   app.js                           # main CLI file
├── names/
│   ├── example.txt                  # group list of names
└── templates/
    └── example.pdf                  # template file for 'example' group
└── output/
    └── example/                     # all the generated pdf under same folder
        └── <candidate name>.pdf     # candidate pdf file named with candidate's name
```

## Disclaimer

The [Alpismo Giovanile](https://it.wikipedia.org/wiki/Alpinismo_giovanile) committee ([Club Alpino Italiano](https://en.wikipedia.org/wiki/Club_Alpino_Italiano)) release a diploma to every attendee at the end of every activity year.

The goal was speed up the generation of each certificate limiting the work of designer just to make the template.
