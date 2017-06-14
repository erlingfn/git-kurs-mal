# Sommerprosjekt 2017

Tilhører Git-kurs for sommerprosjektet 2017

(http://memeshappen.com/media/created/One-does-not-simply-understand-git-meme-60285.jpg)

Skriveleif

## Oppgave 1
Lag en liten feature

- Lag en ny branch utifra master med navn ”feature-<branch_navn>"
- Legg til en ny linje i README.MD
- Commit med passende melding
- Push opp branchen til repoet

## Oppgave 2
Fiks en liten bug

- Lag en ny branch utifra master med navn ”bugfix-<branch_navn>”
- Gjør om linjen ”Skriveleif” til ”Skrivefeil” i README.MD
- Commit med passende melding
- Push opp branchen til repoet

## Oppgave 3
Fiks en merge-konflikt

Lag ny lokal branch med navn <lokalt_branch_navn> som er koblet mot remote branch med 
navn <remote_branch_navn>:
```git checkout -b <lokalt_branch_navn> origin/<remote_branch_navn>```

- Hent ned branchene "conflict-branch-1" og "conflict-branch-2"
- Merge "conflict-branch-2" inn i "conflict-branch-1"
- Løs konfliktene med konflikhåndteringsverktøy i IntelliJ (ikke push opp resultat)

## Oppgave 4
Lag en merge request

- Lag en merge request for branchen du lagde i oppgave 1.
- Få noen andre til å ta "code-review" på endringen du lagde
    - Personen skal lage minst en kommentar på en vilkårlig linje i "changes"-view
- Personen skal akseptere merge-requesten