title: OpenFisca à la CNAF
author:
  name: Merci, l'équipe OpenFisca - Hack'allocs
  url: https://github.com/cbenz/openfisca-hackallocs
output: slides.html

--

# Simulation socio-fiscale
## avec OpenFisca à la CNAF

--

### OpenFisca

- 1 modèle ouvert de la législation socio-fiscale
- contributif / logiciel libre / dév. sur github
- outil neutre pour un débat public apaisé / éclairé

http://www.openfisca.fr/

--

### Jusqu'ici

- OpenFisca simule des *cas types*
- sous-tend des produits comme mes-aides.gouv.fr
  1. je rentre ma situation
  1. à quelles aides ai-je droit ?
- permet de simuler des *réformes*

--

### Aujourd'hui

- OpenFisca *nourri* des données d'entrée réelles
- calcul de l'allocation de rentrée scolaire
- comparaison des résults OpenFisca avec les données réelles
- idéal pour tester les effets *réels* de réformes

--

### Perspectives

- connecter OpenFisca aux données réelles CNAF
- de façon permanente
- proposer une API simulation publique
- proposer une interface web cliente
- garantir le respect de l'anonymat en sortie

--

### Entrer une réforme

<img src="reforms-tester-1.png" width="50%">

--

### Recherche

- Sur les personnes touchées
- Sur les allocataires d'un département
- Selon la composition familiale

--

### Analyse

<img src="reforms-tester-2.png" width="50%">

--

### Utilisateurs

- chercheurs
- élus locaux
- data journalists
- agent public d'une administration
- citoyen éclairé
- société civile (associations, think tanks)
- partis politiques
- cabinets ministériels / Parlement


--

### Nos souhaits

- après http://data.caf.fr/
  - http://simulation.caf.fr/openfisca/
- organiser une journée de dév. interne CNAF
- itérer sur le testeur de réformes
- pouvoir travailler sur l'ERFS anonymisé
