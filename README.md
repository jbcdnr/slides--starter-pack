# Quick start for [slides](https://github.com/tvogels/slides)

This repository is a starter pack to create a new deck of slides. Follow these steps to create and build a new deck:

- Clone this repo with its submodules

```
git clone --recursive git@github.com:jbcdnr/slides--starter-pack.git slides--your-deck-name
```

- Optional: update the library submodules
```
git submodule update --remote
git commit -m "Update slides lib to latest commit"
```

- Optional: change remote repo to a new repo

```
git remote set-url origin <REPO URL>
```

- If you are using Sketch, you can automaticaly build the deck when you save the file `slides.sketch`

```
./sketch-generate.sh .
```

- Serve the deck

```
parcel index.html
```

