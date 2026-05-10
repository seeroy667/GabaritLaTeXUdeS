# GabaritLaTeXUdeS
Gabarit de rappot LaTeX pour le département de génie informatique et électrique de l'Université de Sherbrooke. Les  spécifications sont celles du "Guide de rédaction technique en génie" de  Jean-Philippe Gouin.

Pour utiliser ce document, veuillez explorer de votre plein gré le template fourni. Si vous utilisez  Overleaf, pour éviter un time out, veuillez suivre les étapes suivante:
- Compiler individuellement chaque document (subfiles).
- Compiler le main.tex en ayant commenter certaines plus grosses sections (dans ce gabarit, c'est la section développement)
- Recompiler ces plus grosses sections individuellement.
- Recompiler le main.
La raison pour toute ces manipulations se cache derrière la manière dont la compilation séparée fonctionne avec les subfiles. Il faut compiler chaque subfile, puis les linker (i.e. compiler le main). Le linker doit se faire avec chaque fichier, donc il se peut qu'il faille compiler le main plusieurs fois en commentant certaines sections et en les rajoutant au fur et à mesure. Les  commandes qui rendent le document long à compiler sont les diagrammes modelés avec tikz. Si jamais vous avez du mal à compiler avec ceux-ci, veuillez les mettre en commentaires.