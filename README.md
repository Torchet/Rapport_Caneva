# Introduction
Ce dépôt a pour but de fournir un caneva simple pour les rapports de laboratoire dans un format LaTex. Il contient une structure de dossier permettant de réunir le traitement des données, leurs résultats et l'intégration au rapport.
# Contenu
* Bibliographie : Dossier comprenant le .bib ainsi que les pdfs/word référencés dans le .bib (Le .bib contient des références qui servent d'exemples)
* Graphiques    : Dossier contenant les graphiques et images que vous voulez inclure dans votre rapport, il est déjà référencé dans le .tex ce qui évite de devoir taper le chemin de dossier complet
* PdG           : Dossier contenant votre Page de Garde dans un .tex
* Preambule     : Dossier contenant vos importations de package, il contient déjà les extensions que j'ai utilisée tout au long de mon parcours
* Tables        : Dossier contenant vos tables de données, cela peut être bien si vous voulez les inclures/exclures au dernier moment
* U_C_Code.ipynb: Fichiers de traitement de donnée sous forme de Jupyter Notebook, c'est à partir de ce fichier que vous aller généré vos graphiques et tables dans leurs dossiers respectifs
* U_C_Rapport.tex: Fichier contenant le corps principal du .tex.
# Utilisation
Pour l'utiliser, il vous faudra le cloner et supprimer le .git pour en faire votre dossier séparé. Sentez-vous libre de crée votre propre dépôt à  partir de **votre dossier**.
# Amélioration
N'essayer pas de commit pour faire des changements, ils ne seront pas acceptés. Si vous penser à des choses à rajouter des fonctionnalités ou des examples de codes qui pourrait être utile, je vous encourage à crée une branche et modifier celle-ci ou à m'en faire part par 
message.
Je verrais s'il sera possible de l'intégrer au main ou pas.
# Information
Le caneva a été fait dans le cadre de mes études de bachelor Microtechnique à l'HEPIA. J'ai utilisé Visual Studio Code avec l'extension [LaTeX-Workshop](https://github.com/James-Yu/LaTeX-Workshop). Ainsi que Python et Jupyter pour le traitement des données
