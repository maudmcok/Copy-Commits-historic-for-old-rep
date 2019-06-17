# Simply copy the history of an old directory to a new one <br />


## Instructions
1) Clone  projet
> ``` git clone <oldURL> ```  <br />
2) go to projet folder
> ``` cd <folder old repo> ```  <br />
3) Remove old remote origin of projet.
> ``` git remote remove origin ```  <br />
4) Add new remote of projet.
> ``` git remote add origin <nouveau repo URL> ```  <br />
5) Emable histories of old projet.
> ``` git pull origin master --allow-unrelated-histories```  <br />
6) Update new projet.
> ``` git push -f origin master```  <br />
7) enjoy 😁
