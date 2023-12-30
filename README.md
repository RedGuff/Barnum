# Barnum
Make Barnum effect text.

Ma demande à ChatGPT 3.5 :
Tu es un expert en C++. Donne-moi un code source de logiciel en C++, avec "using namespace std;",  qui prend en ligne de commande les entrées suivantes : une langue "lgg", un nom de fichier "file", un nombre "nLignes".  Le logiciel lit ensuite un fichier portant le nom de la langue, et en extrait "nLignes" au hasard, qui seront ensuite affichées et écrites dans le fichier "file".

=> J'ai une erreur ligne 33 : random_shuffle n'est pas défini dans ce scope !

Correction faite selon ce que me propose ChatGPT (avec explications), cela marche !
