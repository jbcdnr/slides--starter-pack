# Quick start for [slides](https://github.com/tvogels/slides)

This repository is a starter pack to create a new deck of slides. Follow these steps to create and build a new deck:

- Use this [Github repository](https://github.com/jbcdnr/slides--starter-pack) as a template
- Clone it with submodules

```
git clone --recursive [URL to your deck repo]
```


- Optional: update the library submodules
```
git submodule update --remote
git commit -m "Update slides lib to latest commit"
```

- If you are using Sketch, you can automaticaly build the deck when you save the file `slides.sketch`

```
./sketch-generate.sh .
```

- Serve the deck

```
parcel index.html
```

