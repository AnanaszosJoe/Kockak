# Git verziókezelés

- Helyi repo inicializálása:
    > git init
- Helyi repo állapotának ellenőrzése (piros?):
    > git status
- Commitolás előkészítése, színpadra (stage) helyezés, indexelés:
    > git add . (a 'pont' minden állományra vonatkozik)
- Újabb helyi ellenőrzés (zöld?):
    >git status
- Commit, az új verzió létrehozása:
    > git commit -m "firstCommit" (Helyi repo inicializálása)
- Commit ellenőrzés:
    > git status
- Távoli repo létrehozása (a GitHub oldalon)
- Távoli és helyi repo összekapcsolása:
    > git remote add origin https://token@github.com/ananaszosjoe/testrepo.git
- Kiválasztjuk az ágat (branch) a távoli repoban:
    > git push -u origin master (régen main) (első alkalommal)

    > git push (továbbiakban)
- Token használata (GitHubos azonosításunk)

## Publikálás

- Publikálandó fájl neve: index.html
- Settings/Pages/Branch/Master majd Save
- Action-ben látható a publikálási folyamat