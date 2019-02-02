This is a my collection of LaTeX tempates that I use for writing alsmost all my documents. So far it includes two files: one for single-lingual 
purposes (std_artcl) and one for multi-lingual purposes (multi_std_artcl).

Common Packages and Configuration
====================================

This list includes packages that are pre-loaded in every template:

* `mathtools`, `amssymb` and `amsthm`
* `enumitem` 
* `biblatex`
* `xpatch`
* `abstract`
* `xcolor`
* declaring `min/max` math operators
* redefining `eqref` command and the `abstract` and `title` environments
* creating `lemma`, `proposition` and `definition` environments

Template-related Packages
===========================

* the `std_artcl` template should be compliled with the `pdflatex` engine, whereas the `multi_std_artcl` requires `xelatex/lualatex` engines
* `std_artcl` loads `babel`, `inpuntenc` (with `utf8` option) and `fontenc` (with `T1` option), whereas `multi_std_artcl` loads `polyglossia` and `unicode-math`
* `std_artcl`  uses the STIX font (by loading the `stix` package), whereas `multi_std_artcl` uses `GFS Neohellenic` font for both text and math
