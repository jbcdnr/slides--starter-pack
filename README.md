# Quick start for [slides](https://github.com/tvogels/slides)

This repository is a starter pack to create a new deck of slides. Follow these steps to create and build a new deck:

- use this [Github repository](https://github.com/jbcdnr/slides--starter-pack) as a template
- clone the original [slides repository](https://github.com/tvogels/slides)

```
git clone https://github.com/tvogels/slides.git
```

- Add your new deck to `decks`

```
cd slides/decks
git submodule add <YOUR-NEW-DECK-GIT-REPO> 2020-04-03-NEW-DECK
cd 2020-04-03-NEW-DECK
```

- If you are using Sketch, you can automaticaly build the deck when you save the file `slides.sketch`

```
../../sketch-generate.sh .
```


- Serve the deck

```
parcel index.html
```

