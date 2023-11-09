<p align="center">
  <a href="https://github.com/username/project/blob/master/README_EN.md"><img alt="English" src="https://img.shields.io/badge/English-informational"></a> 
  <a href="https://github.com/username/project/blob/master/README_ES.md"><img alt="Spanish" src="https://img.shields.io/badge/Spanish-informational"></a> 
  <a href="https://github.com/username/project/blob/master/README_DE.md"><img alt="German" src="https://img.shields.io/badge/German-informational"></a> 
  <a href="https://github.com/username/project/blob/master/README_JP.md"><img alt="Japanese" src="https://img.shields.io/badge/Japanese-informational"></a>
</p>

![Illustration](src/illustration.png)

# Guide complet des commandes Markdown Discord


[![made by MUCKA](https://img.shields.io/badge/made%20by-MUCKA-orange)](https://mucka.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)
[![Discord](https://img.shields.io/badge/Join-Discord-7289DA)](https://discord.com)




> Vous souhaitez ajouter de la personnalité à vos conversations textuelles quotidiennes ? Vous avez de la chance ! Discord utilise Markdown, un système simple de formatage de texte brut qui vous aidera à **mettre en valeur vos phrases**. Voici comment faire ! Ajoutez simplement quelques caractères avant et après le texte souhaité pour modifier votre texte. Je vais vous montrer quelques exemples...

**Contenu de ce guide :**

- [Formatage de texte](#formatage-de-texte)
- [Formatage de texte organisationnel](#formatage-de-texte-organisationnel)
  - [En-têtes](#en-têtes)
  - [Liens masqués](#liens-masqués)
  - [Listes non ordonnées](#listes-non-ordonnées)
  - [Listes ordonnées](#listes-ordonnées)
- [Blocs de code](#blocs-de-code)
- [Citations de bloc](#citations-de-bloc)
- [Balises Spoiler](#balises-spoiler)
- [Mise en évidence de la syntaxe](#mise-en-évidence-de-la-syntaxe)

## Formatage de texte

| Style                    | Syntaxe         |
|--------------------------|-----------------|
| *Italique*               | \*italique*     |
| __*Italique souligné*__   | \__\*italique souligné*__  |
| **Gras**                 | \*\*gras**      |
| __**Gras souligné**__     | \__\*\*gras souligné**__  |
| ***Gras italique***      | \*\*\*gras italique***  |
| __***Gras italique souligné***__ | \__\*\*\*gras italique souligné***__  |
| __Souligné__             | \_\_souligné__  |
| ~~Barré~~                | \~\~Barré~~     |

>Vous ne voulez pas utiliser Markdown ? Vous pouvez ajouter un antislash `\` devant votre déclaration ou placer votre message dans un bloc de code, et cela échappera au formatage Markdown. Vous verrez ces astérisques comme vous le souhaitez !

## Formatage de texte organisationnel

### Titre

Pour créer un en-tête, vous devez inclure un nombre spécifique de caractères dièse (#). Utilisez (#) pour un grand en-tête, (##) pour un en-tête plus petit, ou (###) pour un en-tête encore plus petit comme premier(s) caractère(s) sur une nouvelle ligne.

| Syntaxe      |
|--------------|
| # Titre 1    |
| ## Titre 2   | 
| ### Titre 3  |


### Liens masqués

Vous pouvez utiliser des liens masqués pour rendre un texte cliquable ou appuyable. Pour ce faire, vous devez inclure le texte que vous souhaitez afficher entre crochets, puis l'URL entre parenthèses. Par exemple :

![liens masqués](https://exemple.com/liens-masqués.png)

Si vous ne souhaitez pas intégrer un lien, vous pouvez envelopper le lien avec `<>` pour supprimer l'intégration pour ce lien spécifique.

### Listes non ordonnées

Vous pouvez créer une liste à puces en utilisant (-) ou (\*) au début de chaque ligne. Vous pouvez indenter votre liste en ajoutant un espace avant (-) ou (\*) au début de chaque ligne.

![listes non ordonnées](https://exemple.com/listes-non-ordonnées.png)

### Listes ordonnées

Pour créer une liste ordonnée, ajoutez des éléments de liste avec des chiffres suivis de points. Les chiffres ne doivent pas être dans l'ordre numérique, mais la liste commencera toujours par le premier numéro. Vous pouvez indenter votre liste en ajoutant un espace avant le chiffre au début de chaque ligne.

![listes ordonnées](https://exemple.com/listes-ordonnées.png)


## Citations de bloc

La syntaxe pour utiliser des citations de bloc est > ou >>> suivis d'un espace.

**\>** au début d'une ligne de texte, crée une citation de bloc sur une seule ligne.

![citation de bloc d'une seule ligne](https://exemple.com/citation-de-bloc-d-une-seule-ligne.png)

**\>\>\>** au début d'une ligne de texte, crée une citation de bloc multiligne. Tout le texte de `>>>` jusqu'à la fin du message sera inclus dans la citation.

![citation de bloc multiligne](https://exemple.com/citation-de-bloc-multiligne.png)

## Balises Spoiler

Vous pouvez marquer manuellement des spoilers en utilisant la syntaxe `||` autour de votre texte ou en tapant `/spoiler` avant votre message. Cela est également annulé par un bloc de code.

![balises spoiler](https://exemple.com/balises-spoiler.png)

## Blocs de code

Discord prend également en charge les blocs de code. Vous pouvez créer vos propres blocs de code en enveloppant votre texte dans des backticks (\`)

![blocs de code en ligne](https://exemple.com/blocs-de-code-en-ligne.png)

Vous pouvez également utiliser trois backticks (\`\`\`) pour créer des blocs de code multilignes, comme ce haïku magnifiquement écrit.

![blocs de code multilignes](https://exemple.com/blocs-de-code-multilignes.png)


## Mise en évidence de la syntaxe

Si vous souhaitez vraiment améliorer vos blocs de code, vous pouvez indiquer un langage spécifique pour **la mise en évidence de la syntaxe**, en tapant le nom du langage que vous souhaitez que le bloc de code attende juste après les trois premiers backticks commençant votre bloc de code. Un exemple...

![mise en évidence de la syntaxe](https://exemple.com/mise-en-évidence-de-la-syntaxe.png)

Il existe de nombreux langages différents en dehors de Markdown que la prise en charge de la syntaxe de Discord. Chaque langage différent a sa propre approche de la syntaxe mise en évidence. Notez que vous ne pourrez pas voir la mise en évidence de la syntaxe sur l'application mobile.

### AsciiDoc
> [!NOTE]  
> AsciiDoc est un langage de balisage léger proche du langage Markdown, proposant une richesse sémantique similaire à DocBook.
```asciidoc
[.code]
====
= Exemple de code Asciidoc

Ceci est un exemple de code Asciidoc.
====
```
---
### AutoHotkey
> [!NOTE]  
> AutoHotkey est un langage de script léger pour l'automatisation de tâches sous Windows.

---
```autohotkey
; Exemple de script AutoHotkey
MsgBox, Bonjour, ceci est un exemple AutoHotkey.
```
---
### Bash
> [!NOTE]  
> Bash est un shell Unix et un langage de script de commande couramment utilisé dans les systèmes d'exploitation Linux et macOS.
```bash
# Exemple de script bash
echo "Bonjour, ceci est un exemple de script bash."
```
---
### CofeeScript
> [!NOTE]  
> CoffeeScript est un langage de programmation qui se compile en JavaScript.

```coffeescript
# Exemple de code CoffeeScript
square = (x) -> x * x
console.log square 3
```
---
### C++
> [!NOTE]
> C++ est un langage de programmation polyvalent et puissant utilisé pour le développement de logiciels système, d'applications, de jeux et bien plus encore.
```cpp
// Exemple de code C++
#include <iostream>
using namespace std;

int main() {
   cout << "Bonjour, ceci est un exemple de code C++." << endl;
   return 0;
}
```
> [!IMPORTANT]  
> Le langage C++ est souvent appelé CPP dans de nombreux contextes.
---
### C#
> [!NOTE]  
> C# est un langage de programmation orienté objet développé par Microsoft.

```csharp
// Exemple de code C#
using System;

class Program {
    static void Main() {
        Console.WriteLine("Bonjour, ceci est un exemple de code C#.");
    }
}
```
---
### Css
> [!NOTE]  
> CSS est un langage de feuille de style utilisé pour décrire la présentation d'un document écrit en HTML ou XML.
```css
/* Exemple de code CSS */
body {
    background-color: lightblue;
    color: darkblue;
    font-family: Arial, sans-serif;
}
```
---
### HTML
> [!NOTE]
> HTML (HyperText Markup Language) est le langage standard utilisé pour créer des pages Web.
```html
<!DOCTYPE html>
<html>
<head>
    <title>Titre de la page</title>
</head>
<body>

<h1>Ceci est un exemple de code HTML</h1>
<p>C'est une page Web de démonstration.</p>

</body>
</html>
```
---
### Diff
> [!NOTE]  
> Diff est un format de données informatiques qui affiche les différences entre deux ensembles de données.

```diff
*** un commentaire
- Exemple de code diff
- Ancienne ligne
+ Nouvelle ligne
--- un autre commentaire

```
---
### Fix
> [!NOTE]  
> FIX (Financial Information eXchange) est un langage de messagerie électronique largement utilisé pour les transactions financières.
```fix
# Exemple de code FIX
8=FIX.4.2 | 9=178 | 35=0 | 34=1 | 49=BRKR | 56=INVMGR | 52=19980604-07:59:56 | 112=19980604-07:59:56 | 10=103 |
```
---
### GLSL
> [!NOTE]  
> GLSL (OpenGL Shading Language) est un langage de programmation de shaders hautement spécialisé utilisé pour écrire des programmes de rendu pour GPU.
```glsl
// Exemple de code GLSL
#version 330 core
layout(location = 0) in vec3 position;
layout(location = 1) in vec3 color;
out vec3 ourColor;
void main() {
    gl_Position = vec4(position, 1.0);
    ourColor = color;
}
```
---
### INI
> [!NOTE]  
> Les fichiers INI (Initialisation) sont des fichiers de configuration textuels simples pour les logiciels.
```ini
; Exemple de fichier INI
[Section]
cle=Valeur
```
---
### Json
> [!NOTE]  
> JSON (JavaScript Object Notation) est un format de données couramment utilisé pour échanger des données entre un serveur et un client web.
```json
{
  "key": "value",
  "another_key": "another_value"
}
```
---
### Markdown
> [!NOTE]  
> Markdown est un langage de balisage léger souvent utilisé pour formater du texte sur le web.

```markdown
<!-- Exemple de texte Markdown -->
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3

- Liste
- Liste
- Liste
```
---
### Ocaml
> [!NOTE]  
> OCaml est un langage de programmation fonctionnel avec un système de types statique, de liaison forte et d'inférence de types.
```ocaml
(* Exemple de code OCaml *)
print_endline "Bonjour, ceci est un exemple de code OCaml."
```
---
### Prolog
> [!NOTE]  
> Prolog est un langage de programmation logique largement utilisé pour l'intelligence artificielle et le traitement du langage naturel.
```prolog
% Exemple de code Prolog
pere(jean, marc).
pere(marc, jules).
```
---
### PowerShell
> [!NOTE]  
> PowerShell est un langage de script et un interpréteur de commandes conçu par Microsoft.
```powershell
# Exemple de code PowerShell
Write-Host "Bonjour, ceci est un exemple de code PowerShell."
```
---
### Python
> [!NOTE]  
> Python est un langage de programmation interprété, de haut niveau, polyvalent et axé sur la lisibilité du code.
```python
# Exemple de code Python
print("Bonjour, ceci est un exemple de code Python.")
```
---
### LaTeX
> [!NOTE]  
> LaTeX est un langage de composition de documents couramment utilisé pour la production de documents scientifiques et mathématiques.
```latex
% Exemple de code LaTeX
\documentclass{article}
\begin{document}
Bonjour, ceci est un exemple de code LaTeX.
\end{document}
```
---
### Excel
> [!NOTE]  
> Excel est un logiciel de tableur développé par Microsoft, largement utilisé pour la manipulation et l'analyse de données.

```excel
// Exemple de formule Excel
=A1+B1
```
---
### XML
> [!NOTE]  
> XML (eXtensible Markup Language) est un langage de balisage utilisé pour le stockage et l'échange de données structurées.
```xml
<!-- Exemple de code XML -->
<root>
    <element>
        Contenu de l'élément
    </element>
</root>
```
---
### YAML
> [!NOTE]  
> YAML est un format de sérialisation de données lisible par l'homme utilisé pour les configurations de programmes et les données structurées.
```yaml
# Exemple de code YAML
key: value
another_key: another_value
```

Et vous avez compris ! Maintenant, vous êtes un **expert en Markdown textuel de Discord**. Sortez et mettez en valeur vos déclarations !

## Remerciements

[Discord](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-)  
[Discord Highlight.js](https://discord.gg/SkZTwPk)

Si vous avez des questions ou si vous souhaitez me contacter, vous pouvez ajouter **matthewzring** sur Discord ou rejoindre [mon serveur Discord](https://discord.matthewzring.dev).
