﻿This repository is for our code in project. Source content is kept separate. Only code and content that  we create by ourselves is put here.
Laita tähän jotain
Klo 15:36 ON NYT
jotain

1. Asenna git koneellesi

2. Kloonaa projekti omalle koneelle

git clone ...polku....

3. Aseta email asetuksiin omalle koneelle

git config --global user.email "...sun osote..."

4. Muuta tiedostoa mitä tarvii ja talleta tiedosto

5. Katso tilanne

git status

6. Lisää muutamasi tiedostot commitoitavien joukkoon

git add ...filename....

7. Päivitä muutokset oman koneen repoon
git commit ..filename... -m "....lisätiedot...."
tai
git commit -a -m "....listätiedot...."

<<<<<<< HEAD
8. Päivitä verkkoon
git push
=======
6. Päivitä verkkoon
git push
>>>>>>> a5781710fb0c913bae62caf212c6129c7423d9e9
