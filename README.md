# Veebiraamistikud 2019

* **Õpetaja:** Tauri Kirsipuu, [tauri.kirsipuu@tlu.ee]
* **Testserver:** lin2.tlu.ee (html, js), greeny.cs.tlu.ee (ssl)

### Ühendus Greeny'sse

* Windows | [VIDEO](https://youtu.be/kg5NAsRQAJ8)

    * [Tunneli loomise juhend](http://minitorn.tlu.ee/~jaagup/kool/java/kursused/09/veebipr/naited/greenytunnel/greenytunnel.pdf)

* Mac OS | [VIDEO](https://youtu.be/RJc-Gvpn9M4)
```
1. open Terminal app
2. write:

ssh university_username@lin2.tlu.ee -L 5555:greeny.cs.tlu.ee:80

3. then write TLU account password. Now you can access greeny from browser localhost:5555

4. open new tab in Terminal (cmd + t) and write:

ssh university_username@lin2.tlu.ee -L 2222:greeny.cs.tlu.ee:22

5. then write TLU account password

5. open FTP client (CyberDuck, FileZilla, Coda etc.) and connect to greeny via SFTP
    host:     127.0.0.1
    port:     2222
    username: YourGreenyUsername
    password: YourGreenyPassword

6. choose one Terminal tab and connect to greeny via ssh, write:
ssh YourGreenyUsername@greeny.cs.tlu.ee
7. then enter your Greeny username password
    ls             – to view files and folders in current path
    cd folderName - to enter folder
    cd ..          – to exit folder to previous path
```

## Kodused tööd
* Kodusteks töödeks on õppetunnis tehtud rakenduste täiustamine omapoolsete funktsionaalsustega. Vabal valikul võib teha 4 kodutööd.


### GitHub'i töövoog

1. *Fork*'i ülesande/projekti repositoorium (leiab [https://github.com/veebiraamistikud-2019/](https://github.com/veebiraamistikud-2019/)).
1. *Clone*'i see repositoorium enda arvutisse/serverisse ja määra repositooriumi URL kuhu edaspidi muudatusi salvestad.
  ```
  git clone https://YOURUSERNAME@github.com/YOURUSERNAME/REPOSITORY.git

  nt esimese iseseisva töö puhul:
  git clone https://jukujuurikas@github.com/jukujuurikas/1kodutoo.git
  ```
1. Lisa vajdusel oma nimi ja email repositooriumi omanikuks ([Setting your username](https://help.github.com/articles/setting-your-username-in-git/)). Vajadusel hangi endale privaatne e-post @users.noreply.github.com lõpuga (https://github.com/settings/emails)
  ```
  git config --global user.name "Tauri Kirsipuu"
  git config --global user.email taurikirsipuu@users.noreply.github.com
  ```
1. Muuda faile ülesande lahendamiseks ja *Commit*'i iga olulisem muudatus, kasutades kahte käsku.
  ```
  git add .
  ```
  ```
  git commit -m "Added this functionality to the app"
  ```
1. Veendu, et kogu kood on *Commit*'itud.
  ```
  git status
  ```
1. *Push/sync*'i muudatused GitHub'i.
  ```
  git push origin
  ```
1. [Ava *pull request*](https://help.github.com/articles/creating-a-pull-request) ülesande originaalses repositooriumis. Järgi üleasende esitamise tähtaega
1. Muudatusi ja täiendusi võib *push*'ida repositooriumisse, kuni ette antud kuupäevani.

Tagasisidet saab otse *pull request*'i millele ootan Sinupoolseid kommentaare/mõtteid/küsimusi. Võid julgselt avada *pull request*'i kohe kui hakkad kodutöö kallal tegelama ja siis kui hätta jääd võid esitada sinna küsimuse. Maini kommentaaris minu kasutajat `@taurikirsipuu` siis jõuan sellele kiiremini vastata.

### Nõuded kursuse läbimiseks

* Igal õppuril tuleb koostada üht raamistikku või selle võimalust tutvustav materjal/näidete kogu ning selle abil kaaslastele läbi viia õppetund. Tööle tuleb saada ja vajadusel õppejõule seletada teiste õppurite seminarides tutvustatud raamistiku põhjal loodud lahendused. 
* Tuleb esitada 4 kodutööd.


### Soovituslik lugemine


### Teemad
T 10.09.2019	16:15 - 17:45 – Angular https://angular.io - Egert Klaamas, Egert Piksar, Kevin Kodasmaa
T 17.09.2019	16:15 - 17:45 – Ember https://emberjs.com - Riho Noormets, Petrik Sarri
T 24.09.2019	16:15 - 17:45 – Ruby on Rails https://rubyonrails.org - Stivo Sirel, Mattias Blehner, Kristjan Veensalu
T 01.10.2019	16:15 - 17:45 – Django https://www.djangoproject.com - Mihkel Haava, Taavi Meinberg, Simon Berner
T 08.10.2019	16:15 - 17:45 – Yii https://www.yiiframework.com/ - eet Triisa, Martin Kasak
T 15.10.2019	16:15 - 17:45 – Laravel https://laravel.com - Henrik Einsar, Simone Niinemägi, Sten Markus Laht
T 29.10.2019	16:15 - 17:45 – Spring https://spring.io - Tauri Taevik, Kert Tamm
T 05.11.2019	16:15 - 17:45 – Meteor https://www.meteor.com - Grete Ojavere, Julika Maiste
T 12.11.2019	16:15 - 17:45 – ASP.NET https://dotnet.microsoft.com/apps/aspnet - Silver Kaugemaa, Katri Palo
T 19.11.2019	16:15 - 17:45 – ReactJS https://reactjs.org - Rasmus Kello, Tim Jaanson, Jaroslava Koger
T 26.11.2019	16:15 - 17:45 – Flask https://palletsprojects.com/p/flask/ - Norman Salong, Kryslin Luks
T 03.12.2019	16:15 - 17:45 – Vue.js https://vuejs.org - 



### Git
* [Become a git guru.](https://www.atlassian.com/git/tutorials/)

## Litsents
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Käesolev <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">leht</span> ja kõik teised https://github.com/eesrakenduste-arendamine-2019 materjalid on <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International Litsensiga</a>.
