# Scanner de ports Python

## Fonctionnement

Le programme demande l'adresse IP d'une cible puis analyse les ports de **0 à 1023** afin de détecter ceux qui sont ouverts.


## Prérequis

- Python 3
- Module `socket`
- Module `threading`
- Module `queue`

## Utilisation

Lancer le programme avec :

```bash
python scanner.py
```

Puis entrer l'adresse IP à analyser :

```text
Entrez l'adresse IP de la cible : 192.168.1.1
```

Le programme affichera ensuite les ports ouverts détectés.

## Exemple

```text
Le port 80 est ouvert
Le port 443 est ouvert

Les ports ouverts sont : [80, 443]
```

## Attention

Utilisez ce programme uniquement sur des machines ou réseaux pour lesquels vous avez l'autorisation d'effectuer un scan.

Écris par Chatgpt et Joshua
