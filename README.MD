# Abakurs, kick-off 2019

# Oppgaver

## Oppgave 0
Start med (https://try.github.io) for å øve på grunnleggende bruk av Git.

## Oppgave 1
Lag en liten feature

- Lag en ny branch utifra master med navn ```feature-<branch_navn>```
- Legg til en ny linje i SOME_FILE.MD
- Commit med passende melding
- Push opp branchen til remote repo
    - Hint: Nye branches lagd lokalt må kobles opp mot en ny branch i remote repo
    ```git push -u origin min-custom-branch```
- Sjekk at branchen eksisterer i remote repo på Github

## Oppgave 2
Fiks en merge-konflikt

- Hent ned branchene ```conflict-branch-1``` og ```conflict-branch-2```
    - Hint: Bruk ```git checkout -b conflict-branch-1 origin/conflict-branch-1```
    for å lage en lokal branch som er koblet opp til samme branch i remote repo. Kjør
    kommandoen for begge branches slik at du har de lokalt.
- Merge ```conflict-branch-2``` inn i ```conflict-branch-1``` og løs konfliktene med
konflikhåndteringsverktøy i IntelliJ
- Commit etter å ha løst merge-konflikt (ikke push opp resultatet)
- Sjekk at det finnes en ny commit i den lokale Git-historikken

## Oppgave 3
Lag en pull request

- Lag en pull request til master for branchen du lagde i oppgave 1.
    - Hint: Hvis du tidligere har pushet en branch til remote så har du kanskje sett
    link til å lage pull request?
- Få noen andre til å ta "code-review" på endringen du lagde
    - Vedkommende skal lage minst en kommentar på en vilkårlig kodelinje
    - Vedkommende skal akseptere pull request inn til master

## Oppgave 4
Now with GUI!

- Gjør oppgave 1 med kun bruk av Git-verktøy i IntelliJ
