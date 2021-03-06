# bootstrap4 Tutorial 01 - BCF

**Priprema za "Bootstrap CSS framework"
Za projekat 001 je potrebno instalirati sledece:**

* **NodeJS** ( Node.js je serverska JavaScript platforma. Instalacioni link https://nodejs.org/en/download/ , a ukratko na Srbskom o tome na linku https://www.popwebdesign.net/popart_blog/2015/06/sta-je-node-js/ )

* **Visual Code Studio** - ( VCS je programesko okruzenje, Instalacioni link https://code.visualstudio.com/Download, A ukratko na Srbskom o tome na linku http://www.manuelradovanovic.com/2015/05/sta-je-microsoft-visual-studio.html )

## Potrebno uraditi pre koriscenja BCF-a

**1. Proveriti da li je NodeJS instaliran na kompu preko CLI-a (Git/CygWin/Terminal/VCS Terminal...) (isto vazi i za Windows/Linux)**

`> node -v`

**2. Napraviti direktorijum i uci u njega:**

`> mkdir bs4 && cd bs4`

**3. Kreiramo datoteku package.json:**

`> npm init -y`

**4. Instaliramo Gulp**

`> npm install --global gulp-cli`

**5. Instaliramo NPM pakete potrebne za projekat**

`> npm install gulp browser-sync gulp-sass --save-dev`

* **gulp** *je java-skript alat za izvrsavanje zadataka kod front-end razvoja. Zvanicna dokumentacija na linku https://gulpjs.com/docs/en/getting-started/quick-start*
* **browser-sync** *automatski obnavlja stranicu u pregledacu kada se izvrsi promena u projektu. Zvanicna dokumentacija na linku https://www.browsersync.io/docs*
* **gulp-sass** *omogucava sastavljanje iz sass-a u projektu. Zvanicna dokumentacija na linku https://www.npmjs.com/package/gulp-sass*

**6. Instaliramo sledece NPM pakete:**

`> npm install bootstrap jquery popper.js --save`

* **bootstrap** *je CSS Framework paket. Zvanicna Bootstrap dokumentacija na linku https://getbootstrap.com/docs/4.3/getting-started/introduction/ - i kratak opis o istom na Srbskom https://www.vps.ns.ac.rs/wp-content/uploads/2018/12/09_Bootstrap.pdf*
* **jquery** *je paket koji koristi sam bootstrap. Zvanicna dokumentacija na linku https://api.jquery.com/ , kao i kraca verzija na Srbskom http://webarena.rs/jquery-bukvar*
* **popper.js** *je paket koji takodje koristi bootstrap. Dozvoljava pozicioniranje, razne efekte koji doprinose da projekat izgleda bogatije. Zvanicna dokumentacija na linku https://popper.js.org/popper-documentation.html*

**7. Sada kopiramo projekat preko git comande**

`> git clone https://github.com/promotion-systems/bootstrap4-tut1.git`

**8. I na kraju pokrenemo Gulp preko komande**

`> gulp`

## Ostali korisni linkovi  

* **Osnove HTML-a:** http://webarena.rs/uvod-u-html
* **Osnove CSS-a:** http://webarena.rs/uvod-u-css
* **Osnove JavaScrip-a:** http://webarena.rs/javascript-jezik-weba
* **Zvanicna dokumentacija za NPM (Node Package Manager):** https://docs.npmjs.com/
* **Zvanicna dokumentacija za SASS:** https://sass-lang.com/documentation/file.SASS_REFERENCE.html
* **Zvanicna dokumentacija za Git:** https://git-scm.com/doc
* **Zvanicna dokumentacija za VCS (Visual Code Studio):** https://code.visualstudio.com/docs
* **Zvanicna dokumentacija za Font Awesome:** https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use
* **Zvanicna dokumentacija za Google Fonts:** https://fonts.google.com/about i https://design.google/library/google-fonts/?utm_source=Google&utm_medium=Fonts&utm_campaign=Article%20Tab
* **Zvanicna dokumentacija za JSON na Srbskom:** https://www.json.org/json-sr.html



