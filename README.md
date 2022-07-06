# happyfind
Project of our CDA training

[MASTER BRANCH] no direct push on it


- 1 commit par pull-request
- 2 pas de push directs sur les branches principales
- 3 pour faire un push -> git add (les fichiers souhaités) -> git commit -m 'conventional commit' -> git push origin [la task branch]
                       -> git rebase -i (develop) -> replace picks par reword pour le premier et fixup pour tous les autres 
                       -> git push origin [la task branch] -f (-f force sinon github pas content)
