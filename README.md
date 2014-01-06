# clojure-extra-pack

An [emacs-live](https://github.com/overtone/emacs-live) pack containing some extras for Clojure development:

* [ritz-nrepl](https://github.com/pallet/ritz/tree/develop/nrepl)
* [nrepl-inspect](https://github.com/vitalreactor/nrepl-inspect)

## Installation

Don't forget the submodules:

    git submodule init
    git submodule update
    
Assuming `~/.live-packs/clojure-extra-pack`, create `~/.emacs-live.el` file and include:

    (live-add-packs '(
      "~/.live-packs/clojure-extra-pack"))
