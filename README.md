# CrackMe05
## Shake ton bool
![BoolShake](shake.gif)

### Objectif :
Accéder à la section Premium

### Prérequis :
- Java 11 (8 fonctionne aussi normalement)
- Les SDK Tools installés sur votre ordinateur
- Un téléphone physique lié à votre ordinateur ou un émulateur (Android 11, x86, Google APIs)
- APKTool
- JD-GUI
- Dex2Jar

### Déroulement :
Téléchargez et installez la release stockée sur ce repo
OU
Récupérez le code source (sans le lire) et générez une archive de l'application

### Règles :
- Interdit de lire le code source


### Indices menant à la solution :

<details>
  <summary>1er indice</summary>

  Les étapes pour résoudre cette énigne sont les suivantes :
  - Décompilation de l'application (Apktool + Dex2Jar)
  - Analyse du code (JD-GUI)
  - Edition du code (langage smali)
  - Recompilation et signature (Apktool + Zipalign + Apksigner)
</details>
<details>
  <summary>2eme indice</summary>

  Les models contiennent très souvent des Booleans qui permettent de définir les accès aux différentes parties de l'application

</details>
<details>
  <summary>3eme indice</summary>

  En Smali, 0x0 = false et 0x1 = true

</details>