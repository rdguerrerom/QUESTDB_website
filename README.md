# QUEST Website

This repository contains the QUEST  database, and a web application to
plot  statistical  indicators.   The  web   app  is  built  using  the
[hugo](https://gohugo.io/)   static   website   generator   with   the
[beautifulhugo](https://themes.gohugo.io/beautifulhugo/) theme.

All the data are stored in the [static/data](static/data) directory.

## Requirements

- [Hugo >= 0.48](https://gohugo.io/getting-started/installing/#quick-install)

## Quick start

To clone this website and use it locally, run the following commands.

```bash
git clone --recurse-submodules https://github.com/LCPQ/QUESTDB_website/
cd QUESTDB_website
make serve
```

Now you can use your browser to  navigate to the website using the URL
given by Hugo in your terminal (http://localhost:1313/QUESTDB_website/)

## The QUEST database

The  QUEST  website  has  been  designed to  gather  and  analyze  the
highly-accurate vertical  excitation energies  produced by  the [QUEST
project](https://doi.org/10.1021/acs.jpclett.0c00014).     The   QUEST
database contains more than  470 accurate vertical excitation energies
of  various  natures  ($\pi  \to \pi^{*}$,  $n  \to  \pi^{*}$,  double
excitation, Rydberg,  singlet, doublet,  triplet, etc) for  small- and
medium-sized  molecules.   These values  have  been  obtained using  a
combination of  high-order coupled cluster and  selected configuration
interaction calculations using increasingly  large diffuse basis sets.
One of the key aspect of the QUEST dataset is that it does not rely on
any experimental  values, avoiding potential biases  inherently linked
to  experiments  and facilitating  in  the  process theoretical  cross
comparisons.  Following this composite protocol,  we have been able to
produce theoretical  best estimates (TBEs) with  the aug-cc-pVTZ basis
set, as  well as  basis set  corrected TBEs  (i.e., near  the complete
basis set limit) for each of these transitions.  Thanks to the present
website,  one can  easily test  and compare  the accuracy  of a  given
method with respect to various variables  such as the molecule size or
its family,  the nature of the  excited states, the size  of the basis
set, etc.


## Bug reports

Please report problems/bugs on the [GitHub issue tracker](https://github.com/LCPQ/QUESTDB_website/issues).

## Licenses

This QUESTDB database is made available under the Open Database License:
http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual
contents of the database are licensed under the Database Contents License:
http://opendatacommons.org/licenses/dbcl/1.0/

The web application is made available under the BSD 3-clause license.

----------
<img src="./static/img/ERC.jpg" width="200">
This project has received funding from the [European Research Council (ERC)](https://erc.europa.eu)
under the European Union's Horizon 2020 research and innovation programme (Grant agreement No. 863481).


