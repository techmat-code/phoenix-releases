<p align="center">
  <img src="https://raw.githubusercontent.com/techmat-code/phoenix-releases/main/phoenix.png" alt="Phoenix" width="160">
</p>

<h1 align="center">Phoenix</h1>
<p align="center"><b>Votre technicien informatique, directement sur votre PC Windows.</b><br>
Un logiciel <b>TechMat Support</b></p>

---

## Qu'est-ce que Phoenix ?

Phoenix aide les personnes qui ne sont pas à l'aise avec l'informatique à comprendre et à réparer les
problèmes de leur ordinateur Windows 11, avec des mots simples.

- **Dites ce qui ne va pas** avec vos mots (« internet ne marche plus », « mon PC rame ») ou montrez une
  capture du message d'erreur : Phoenix comprend et vous pose au plus 3 questions.
- **Diagnostic clair** : vert, tout va bien ; orange, à surveiller ; rouge, il y a un problème.
- **Réparations avec votre accord** : Phoenix explique ce qu'il va faire, pourquoi et le risque, puis
  vérifie que c'est réparé. Rien n'est modifié sans votre accord.
- **Sécurité / virus** : pilote Microsoft Defender, explique les menaces simplement et surveille l'ordinateur.
- **Boîte noire** : explique les plantages et les arrêts brutaux.
- **Rapports PDF** à garder ou à donner à un technicien.
- **Mises à jour automatiques**, vérifiées (empreinte SHA-256), sans perdre vos données.

## Télécharger et installer

1. Ouvrez la page **[Releases](https://github.com/techmat-code/phoenix-releases/releases/latest)**.
2. Téléchargez **`Phoenix_Setup_<version>.exe`** (rubrique « Assets »).
3. Double-cliquez dessus, puis suivez l'installation (Windows demande l'autorisation : répondez « Oui »).

**Version portable (clé USB)** : téléchargez `Phoenix_Portable_<version>.zip`, décompressez-le sur une clé,
puis lancez `Phoenix.exe` — sans installation.

### Vérifier le fichier téléchargé (facultatif)

Chaque version publie l'empreinte SHA-256 de son installateur (fichier `.sha256` et texte de la version).
Dans PowerShell :

```powershell
Get-FileHash .\Phoenix_Setup_<version>.exe -Algorithm SHA256
```

Le résultat doit être identique à l'empreinte publiée. Phoenix fait lui-même cette vérification avant
chaque mise à jour automatique et refuse un fichier qui ne correspond pas.

> Les fichiers `Phoenix_Setup.exe` / `Phoenix_Setup.exe.sha256` (sans numéro) sont des copies
> identiques, gardées pour la mise à jour automatique des toutes premières installations.

## Configuration nécessaire

- Windows 10 (1809) ou Windows 11, 64 bits
- Connexion Internet seulement pour le technicien IA et les mises à jour

## Confidentialité

Phoenix ne lit pas vos fichiers personnels et n'envoie ni vos fichiers ni vos mots de passe. Les captures
de messages d'erreur sont lues sur l'ordinateur, sans être envoyées.

## Contact

**TechMat Support** — contact.techmat@gmail.com — 07 83 45 64 24

---

<sub>Ce dépôt contient uniquement les versions publiées de Phoenix (installateurs). Le code source n'est pas
publié.</sub>
