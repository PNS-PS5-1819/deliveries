# Recap


:confetti_ball: *BRAVO* ! On voit une nette progression par rapport au "rendu" `first` !! CONTINUEZ !

Vous n'atteignez toujours pas, pour la plupart, les `requirements` du client ; mais les erreurs sont facilement réparables en majorité.


[Pour les résultats par équipe, c'est ici!](https://github.com/PNS-PS5-1819/deliveries/tree/master/second)

__Merci de prendre le temps de lire ce résumé, et de lire les erreurs de vos `reports` avant de vous `unleash` sur `Slack`__

Le script a été `upgradé`: 
les tests sur l'environnement sont renforcés pour votre notifier de tout fichier/dossier qui *n'aurait pas du être versionné*.

une différence entre ce qui est attendu/obtenu est générée, pour vous fournir le plus de détails possible.
Il suffit de cliquer sur l'item en question qui est en :boom: (ici :boom: `Stability`)

Voici un exemple de sortie possible:

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 5
> 4

```
</details>

Cela vous indique que vous n'avez pas `crashé` quand on vous a demandé de générer la stabilité, mais que le `ref` obtient 
```
0
0
```

et vous
```
5
4
```

et que donc il doit y avoir une erreur.

*Attention* certaines errreurs peuvent être bêtes: espaces, ligne vide, etc.
Nous avons essayé au maximum de traiter ces cas, pour vous fournir le plus de feedback "intelligents".
En d'autre termes: mëme si vous n'êtes pas `100`% compatibles avec la sortie du `ref` (ex: espace en trop en fin de ligne) ; le script vous répond quand meme `OK`. En revanche, nous avons surement loupé des cas particuliers...
Lisez attentivement les sorties attendues !

### Erreurs majoritaires

#### Non respect des `specs` de format de sortie
en invoquant `./apb.sh` (ou`./student_first.sh`) vous n’affichez pas ce qui est attendu sur la sortie standard. 
Beaucoup rajoute d’autre informations (debug, titre, temps d’execution).
Pour d’autre ce sont simplement des erreurs de formatage (saut de ligne, pas d’espace, etc). 
*Attention* cette sortie standard fait partie des `spec` et donc du contrat avec votre client !! 
Vous ne pouvez pas la changer, pas plus que vous pouvez le format d’entrée !

#### Différences sur les métriques et arrondies
Cette erreur est à prendre avec un pas de recul et à traiter au cas par cas.
- Certains d'entre vous retournent des chiffres à l'ouest de ce que le `ref` retourne (eg `3456796,43542745674587` vs `2.0`) ;
- d'autres ont des erreurs d'arrondis, (`2.349` pour vous vs `2,35` pour le ref)
- d'autres des formats inconsistants: un coup vous renvoyer des chiffres séparés par `.` et un autre coup pas `,`

#### Erreurs par construction
Quand vous `crashez` à l'exécution (ex: "donne moi la distance" --> "IndexOutOfBoundException has been thrown") ; *évidemment* quand on va comparer votre résultat (vide donc) à celui du `ref`, ca va planté :boom:
Nous améliorons sans cesse le script pour éviter ce genre de "bruits" à l'avenir.
