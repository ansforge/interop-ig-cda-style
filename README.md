# interop-ig-cda-style

Template d'Implementation Guide (IG) FHIR de l'ANS, spécifique aux IG de style **CDA**.

- **Identifiant du package** : `ans.cda.fr.template`
- **Canonical** : https://interop.esante.gouv.fr/ig/cda/template
- **Template de base** : `fhir2.base.template`
- **Build continu** : https://ansforge.github.io/interop-ig-cda-style/main/ig

Ce répertoire GitHub permet de fixer la charte graphique des IG de style CDA délivrés par l'ANS.
Il ne permet pas d'être utilisé tel quel et sa modification doit être faite par des experts FHIR.

## Utilisation

Dans le fichier `ig.ini` d'un IG, référencer le template :

```ini
template = ans.cda.fr.template#current
```

Pour créer un IG, le plus simple est de forker [le repo IG-modele](https://github.com/ansforge/IG-modele) puis d'adapter la référence du template.

## Acronymes

FIG : FHIR Implementation Guide

## About

Ce template est issu de la branche `cda` de [ansforge/interop-IG-style](https://github.com/ansforge/interop-IG-style/tree/cda) et a été généré à partir de https://github.com/HL7/ig-template-base
