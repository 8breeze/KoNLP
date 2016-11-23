KoNLP
---------------



[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/KoNLP)](http://cran.r-project.org/package=KoNLP)
[![CRAN Downloads](http://cranlogs.r-pkg.org/badges/KoNLP)](http://cran.r-project.org/package=KoNLP)
![CRAN Downloads Total](http://cranlogs.r-pkg.org/badges/grand-total/KoNLP?color=brightgreen)
[![Travis-CI Build Status](https://travis-ci.org/haven-jeon/KoNLP.svg?branch=master)](https://travis-ci.org/haven-jeon/KoNLP)


POS Tagger and Morphological Analyzer for Korean text based research. It provides tools for corpus linguistics research such as Keystroke converter, Hangul automata, Concordance, and Mutual Information. It also provides a convenient interface for users to apply, edit and add morphological dictionary selectively. 

  - Interfacing with opensource [Hannanum analyzer](http://semanticweb.kaist.ac.kr/home/index.php/HanNanum).
  - Some twiks are applied on [Hannanum analyzer](https://github.com/haven-jeon/HanNanum-Analyzer) for bigger or flexible user dictionary for [Sejong project](http://www.sejong.or.kr/) and [NIADic](https://github.com/haven-jeon/NIADic). 
  - Many other functions for Korean text analysis like keystroke conversion, is.jamo, is.hangul, Hangul antomata...   

Some of Korean tutorials are on [my blog](http://freesearch.pe.kr), English pages are mainly on [wiki](https://github.com/haven-jeon/KoNLP/wiki).

To install from CRAN, use

    install.packages('KoNLP')

To install from GitHub, use

    install.packages('devtools')
    devtools::install_github('haven-jeon/KoNLP')

