Creer le 14/08/2022 à 19:48
Modifier sur serveur github 14/08/2022 à 20:04
recupere sur le client avec git pull
Modifier sur le client le 14/08/2022 à 20:10 et pousser sur le serveur avec git push
ne fait rien pcq pas de commit :)  alors git commit -m "commit puis push à 20:12"
Modifie, commit -m "commite à 21:17" et push
Modifie, commit -m "commite à 21:23" et push
modifie, commit -m "commit à 21:30 et push"
modifie sur serveur 15/08/2022 à 9:43
passe sur branch dfrbranch001 et modifie readme.txt, commit et push
Ensuite je repasse sur main, git checkout main afin de pouvoir faire un merge de main avec dfrbranch001
Je verifie que je suis bien sur main avec git branch, la branche sur laquelle je suis est celle avec * en debut
Ensuite je fait 
git merge dfrbranch001
CORP-TALAN+didier.francois@TAL-4V0NMG3 MINGW64 ~/Documents/GITdfrtest (main)
$ git merge dfrbranch001
Updating 95c14c2..196d2c8
Fast-forward
 readme.txt | 1 +
 1 file changed, 1 insertion(+)
et pour pousser sur le serveur alors 
git push
CORP-TALAN+didier.francois@TAL-4V0NMG3 MINGW64 ~/Documents/GITdfrtest (main)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/dfr1965/dfrtest.git
   95c14c2..196d2c8  main -> main
