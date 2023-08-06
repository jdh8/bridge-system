Chen-Pang He (jdh8)'s bridge bidding systems
============================================
This repository contains my bidding systems.  These documents are in the Bridge
Bidding Markup Language (BML).  Please use [my fork][fork] for now until
gpaulissen/bml#21 gets fixes.

[fork]: https://github.com/jdh8/bml

The below are my pet forcing club bidding systems.  I believe bidding 1♣ for
all strong hands is a superior treatment.

- [Capoo Polish Club](https://jdh8.github.io/bridge-systems/wj.htm)
- [Modern Blue Club](https://jdh8.github.io/bridge-systems/blue.htm)
- [Defensive bidding system](https://jdh8.github.io/bridge-systems/defense.htm)

Building HTML and BSS files
---------------------------

First, install the BML converters.

```sh
git clone https://github.com/jdh8/bml.git
pip install .
```

Then, `make` whenever you want to generate or update files.

```sh
make -j8
```
