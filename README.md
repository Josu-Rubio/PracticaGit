# PracticaGit
Practiva Git, Github, y Sourcetree

- git reset --hard HEAD~1  --> Usamos --hard para perder todos los cambios en el Working Copy
- git reset --hard (+ref code previo) --> Volvemos al paso anterior con el reset hard para volver a la rama sytled en la posición anterior.
- La información que me proporciona es "Already up to date"
- Me causa el conflicto de "Content", debido a que la información del documento en las ramas no es igual.
- de nuevo "Alrady up to date"
- git log --graph
- Sí, porque están posicionaría el la rama master en la posicion de la rama title sin perder ningún tipo de información.
- git reset HEAD~1 --> Al usar el reset normal (sin --hard) no perdemos el trabajo previo del working copy
- git restore git-nuestro.md
- git branch -D title
- git reset --hard (+ref code previo)
- git reflog --> para averiguar la ref y git checkout (+ ref inicial)
- git reflog --> para averiguar la ref y git checkout (+ ref final)
