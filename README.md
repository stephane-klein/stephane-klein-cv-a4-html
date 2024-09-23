Après avoir tondu un Yak [ici](https://github.com/stephane-klein/typst-sklein-resume-poc), avec [Typst](https://typst.app) pour générer mon CV au format PDF.

Après avoir rédigé un CV trop long [ici](https://sklein.xyz/fr/cv/).

J'ai décidé de produire un CV qui tient sur une feuille A4, implémenté simplement en HTML + CSS.

Je génère la version PDF avec la fonctionnalité d'impression de Chrome.

Cela donne ceci ([version pdf](cv.pdf)) :

<a href="cv.pdf"><img src="cv.png"></a>

Pense bête pour convertir le fichier `cv.pdf` au format `png` :

```sh
$ convert -density 300 cv.pdf -resize 800x -background white -alpha remove -alpha off cv.png
```
