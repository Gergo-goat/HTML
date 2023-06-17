Nyelv beállítása magyarra <html lang=”hu”>
Karakterkészlet beállítása UTF-8-ra <meta charset=”utf-8”>
Lapfül címének beállítása <title>Valami</title>
Külső CSS fájl behivatkozása <link href=”vmi.css” rel=”stylesheet”>
Stílus taggel <style>…</style>
Külső JS fájl behivatkozása <script src=”vmi.js”></scrip
keret + azonosító + osztály(ok)
<div id=”azonosito” class=”osztaly1
osztaly2 stb”>
…
</div>
címsor (1-6. szintű) <h1>…</h1>, <h2>…</h2>, … ,<h6>…</h6>
bekezdés <p>…</p>
sorközi kijelölő elem <span>…</span>
vízszintes vonal <hr/>
sortörés bekezdésen/hosszabb
szövegben
<br/>
számozott lista
<ol>
<li>…</li>
…
</ol>
számozatlan lista
<ul>
<li>…</li>
…
</ul>
táblázat <table>…</table>
táblázat sora
<table>
<tr>…</tr>
</table>
táblázat sorának cellája (oszlop)
<table>
<tr><td>…</td></tr>
</table>
cella kiterjesztése két oszlopnyi
szélesre
<td colspan=”2”>…</td>
cella kiterjesztése két sornyi
szélesre
<td rowspan=”2”>…</td>
hivatkozás (milyen címre=href,
hogyan jelenjen meg=target)
<a href=”hova” target=”_blank”>…</a>
kép + forrás + címke + helyettesítő
szöveg
<img src=”vmi.jpg” title=”címke”
alt=”helyettesítő”>
űrlap <form>…</form>
beviteli mező formban
− szövegre
− e-mailre
− jelszóra
− számokra
− csúszkára (1-5-ig)
− elküldés feliratú gombhoz
<input type=”text”>
<input type=”email”>
<input type=”password”>
<input type=”number”>
<input type=”range” min=”0” max=”5”>
<input type=”submit” value=”elküldés”>
beviteli mező címkéje
<label for=”mezo1”>…</label>
<input type=”text” name=”mezo1”>
gomb <button>Felirat</button>
legördülő lista opciókkal
<select>
<option>…</option>
<option>…</option>
</select>
HTML5 elemek
fejléc (nem fejrész!) <header>…</header>
menü <nav>…</nav>
oldalsáv <aside>…</aside>
cikk <article>…</article>
szekció/szakasz <section>…</section>
lábléc <footer>…</footer>
video vezérlő gombokkal
<video controls>
<source src=”vmi.mp4” type=”video/mp4”>
</video>
audió vezérlő gombokkal
<audio controls>
<source src=”vmi.mp3” type=”audio/mpeg”>
</audio>
CSS TULAJDONSÁGOK ÉS TIPPEK
Funkció CSS tulajdonság és érték(ek)
magasság 100px height:100px;
szélesség 100px width:100px;
külső margó mindenhol 20px margin: 20px;
külső margó fent 20px margin-top: 20px;
külső margó lent 20px margin-bottom: 20px;
külső margó jobbra 20px margin-right: 20px;
külső margó balra 20px margin-left: 20px;
külső margó fent-lent 20px, jobbrabalra auto
margin: 20px auto;
belső margó mindenhol 20px
többit ld. külső margó padding: 20px;
szegély mindenhol sima, vékony,
fekete
border: solid thin black;
szegély alul pontozott, 1px, fehér
többi ld. külső margó border-bottom: dotted 1px white;
blokként jelenjen meg display: block;
sorközi elemként jelenjen meg display: inline;
ne jelenjen meg display: none;
jobbra lebegtetett float: right;
balra lebegtetett float: left;
háttérszín kék background-color: blue;
háttérkép bg.jpg background-image: url(”bg.jpg”);
háttérkép mérete lefedésre background-size: cover;
háttérkép pozíciója középre
vízszintesen és függőlegesen is
background-position: center center;
háttérkép rögzített background-attachment: fixed;
betűszín piros color: red;
betűtípus Arial vagy talpnélküli font-family:Arial,sans-serif;
betűméret 12pt font-size:12pt;
betűstílus dőlt font-style: italic;
szöveg sorkizárt text-align: justify;
szöveg balra zárt text-align: left;
szöveg jobbra zárt text-align: right;
szöveg középre zárt text-align: center;
szöveg nagybetűs text-transform: uppercase;
szöveg aláhúzott text-decoration: underline;
szöveg első sorának behúzása 20px text-indent: 20px;
szövegek közötti sormagasság 25px line-height: 25px;
listaelemek jelölése négyzet list-style: square;
Selectorok
bekezdés html elemekre p{…}
listaelemen belüli bekezdésekre li p{…}
első és második szintű címsorokra h1,h2{…}
osztaly nevű osztályokra .osztaly{…}
azon nevű azonosítóra #azon{…}
link fölé vitt egér a:hover{…}
meglátogatott link esetén a:visited{…}
div-en lévő fókusz esetén div:focus{…}
