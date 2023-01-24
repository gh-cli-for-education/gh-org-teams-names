## Installation

``` 
gh extension install gh-cli-for-education/gh-org-teams-names
```

## Usage

```
➜  gh-org-teams-names git:(main) ✗ gh org-teams-names -h              
USAGE
  gh team-names [-o|--org <orgname>] [-r|--regexp <regexp>] [-e|--exclude <regexp>]
  - Gives the names of the teams in the organization
  - If no organization is given, the current one is used
```

## Examples of usage

```
➜  gh-org-teams-names git:(main) ✗ gh pwd
ULL-MII-SYTWS-2223
➜  gh-org-teams-names git:(main) ✗ gh org-teams-names   
ale_hernandez_liberon-alu0101225562
casiano-rodriguez-leon-alumnoudv4
casiano-rodriguez-leon-crguezl
claudio_nestor-yanes-mesa-alu0101229942
jordi-bas-balcells-alu100965315
parallel-computing-group-parallel
santiago-villar-vazquez-alu0100990522
➜  gh-org-teams-names git:(main) ✗ gh org-teams-names -e 'cas|jor|par'
ale_hernandez_liberon-alu0101225562
claudio_nestor-yanes-mesa-alu0101229942
santiago-villar-vazquez-alu0100990522
➜  gh-org-teams-names git:(main) ✗ gh org-teams-names -r 'cas|jor|par'
casiano-rodriguez-leon-alumnoudv4
casiano-rodriguez-leon-crguezl
jordi-bas-balcells-alu100965315
parallel-computing-group-parallel
```