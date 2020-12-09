# Exercice :three:

- [ ] Change de répertoire

```
$ cd 03
```

- [ ] Ouvre le fichier `programme.py` avec `nano`


```
$ nano programme.py
```

- [ ] Modifier le programme permettant d'imprimer la date au format anglophone "Decembre 09 2020"

remplacer les `???` du code ci-dessous par l'énoncé ci-dessus

```python
# -*- coding: utf-8 -*-
"""

@author: CollegeBoreal
"""

def exo_03(tuple):
  # Ajouter le code permettant d'inverser la tuple
  # sous la forme 'Decembre' 9 2020
  ??? 
  return (b, a , c)

def main():
  print( exo_03( ( 9, 'Decembre' , 2020 ) ) )

if __name__== "__main__":
  main()
```

- [ ] Fais tourner ton programme dans ton terminal

Pour éxécuter le programme Python tape `python programme.py` dans le terminal. Le programme Python doit se trouver dans le même répertoire ou l'on se trouve.

```
$ python programme.py
```

Après l'éxécution, sur ton terminal s'affichera: `('Decembre', 9, 2020)`. Nous ferons encore mieux dans quelques instants mais pour l'instant, il faut soumettre le code vers GitHub. 


- [ ] Soumettre les modifications

Pour chaque changement de fichiers dans ton référentiel, il faut  `ajouter` et `signer` le fichier qui te permet de formuler un message detailant ce que tu as changé. Ensuite tu peux `soumettre` une version mise à jour, en même temps que tes commentaires, vers GitHub. 

:round_pushpin: Faisons ces quatres étapes:

1. Ajouter dans Git: `git add programme.py`
2. Signer dans Git: `git commit -m "Ajout de la fonction exo_03() inversant la date"`
3. Récuperer la correction: `git pull`      
         :bulb: Pour valider la récupération dans `nano` utiliser la combinaison - `^O WriteOut` + `Enter` + `^X Exit`
3. Soumettre à Git: `git push`
4. Revenir au répertoire principal: `cd ..`
