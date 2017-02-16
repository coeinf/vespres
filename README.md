# Vespres al Col·legi

## Afegir contingut

- [Nou track](https://github.com/coeinf/vespres/new/master/_tracks?&value=---%0Atitle%3A%20Nom%20del%20track%0A%23sponsors%3A%0A%23%20%20-%20un-bon-sponsor%0A---%0Abuit%0A%20%20%20)
- [Nova Activitat](https://github.com/coeinf/vespres/new/master/_activities?&value=---%0Atitle%3A%20Nom%20de%20la%20activitat%0Aimage%3A%20https%3A%2F%2Fplaceimg.com%2F800%2F450%2Fnature%0Adate%3A%202099-12-31%20%23%20tbd%0A---%0A%0AInformaci%C3%B3%20sobre%20la%20activitat.%0A%20%20%20)
- Nou Ponent: Botó al contributor [TBD](http://coeinf.github.io/vespres/contributors/tbd)
- Nou Esdeveniment: Botó als [tracks](http://coeinf.github.io/vespres/)
- Nou Emplaçament/Lloc: Botó al [TBD](http://coeinf.github.io/vespres/venues/tbd)
- Nou Meetup Amic: Botó en [qualsevol amic](http://coeinf.github.io/vespres/friends/sudoers-barcelona)

## Setup

Requires ruby and [bundler](http://bundler.io/).

Clone the repository:

```bash
$ git clone ...
```

Enter to the directory and install dependencies:

```bash
$ cd vespres
$ bundle install
```


## Preview

Use bundler to execute jekyll:

```bash
$ bundle exec jekyll s -H 0.0.0.0 --incremental  --baseurl '' -P 4002
```

Open the browser in [localhost:4002](http://localhost:4002) to see the result.
