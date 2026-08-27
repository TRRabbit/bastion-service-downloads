# Bastion Service — téléchargements

Archives officielles de la gamme Bastion, signées et vérifiées.

Ce dépôt ne contient **que les fichiers distribués** : le launcher, ses modules
et leurs notes de version. Le code source n'y est pas.

## Produits

| Produit | Ce que c'est |
|---|---|
| **Bastion Service** | Le launcher de bureau Windows. Installe, met à jour et supervise les modules ci-dessous. C'est par lui qu'on commence. |
| **Guardian ARK** | Bot Discord pour un serveur ARK: Survival Ascended — état du serveur, classements, passe de combat, tickets, anti-triche. |
| **Guardian Palworld** | Le même, pour un serveur Palworld. |
| **Bastion ORP** | Protection des bases hors ligne pour serveur Palworld (plugin serveur). |

## Installation

Téléchargez **Bastion Service** depuis la section *Releases*, puis installez
vos modules depuis la boutique intégrée. Les modules ne s'installent pas à la
main : le launcher vérifie la signature de chaque archive avant de l'ouvrir, et
revient tout seul à la version précédente si une mise à jour échoue.

## Vérifier une archive

Chaque publication porte l'empreinte SHA-256 de son archive dans ses notes de
version. Sous Windows :

```powershell
Get-FileHash .\archive.zip -Algorithm SHA256
```

L'empreinte affichée doit correspondre, caractère pour caractère. Si elle
diffère, n'installez pas le fichier.

## Mises à jour

Le launcher vérifie les nouvelles versions tout seul et vous prévient. Rien à
surveiller ici.
