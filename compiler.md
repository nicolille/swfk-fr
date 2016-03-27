Comment compiler le livre ?

  1. téléchargez les sources en utilisant Mercurial avec la commande : `hg clone https://swfk-fr.googlecode.com/hg/ swfk-fr`
  1. installez la dernière version de XeTeX (la version 0.999.6 est utilisée par MW); cette version est disponible dans la version 2.7 de Miktex et dans la version 2008 de TeX Live (MW utilise TeX Live 2008 installé à partir de http://mirror.ctan.org/systems/texlive/tlnet/2008/ sur une distribution Ubuntu)
  1. installer les dernières versions de Linux Libertine (http://linuxlibertine.sourceforge.net/), Firefly (http://www.study-area.org/apt/firefly-font/) et Dejavu (http://dejavu-fonts.org/wiki/index.php?title=Main_Page); sous Linux MW copie les fonts OTF dans son répertoire ~/.fonts que XeTeX sait utiliser
  1. compiler avec la commande : `xelatex swfk.tex`
  1. les autres outils Latex sont utilisés pour la création de l'index par exemple