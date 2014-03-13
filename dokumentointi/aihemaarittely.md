# Aihem‰‰rittely

# Aihe

Toteutetaan ohjelma, joka auttaa turnausj‰rjest‰j‰‰ organisoimaan turnauksen riippumatta siit‰, mink‰ lajin tai pelin turnaus on kyseess‰. 

# K‰ytt‰j‰t

Turnausj‰rjest‰j‰

# Aiotut toiminnallisuudet

1. Ohjelma pyyt‰‰ k‰ytt‰j‰‰ aluksi valitsemaan halutun turnausmuodon. Aluksi ainoa muoto on KO, mutta t‰t‰ voidaan laajentaa myˆhemmin sis‰lt‰m‰‰n myˆs Swiss ja kenties muitakin.
2. Ohjelma kysyy k‰ytt‰j‰lt‰, montako pelaajaa turnaukseen osallistuu.
3. Ohjelma kysyy k‰ytt‰j‰lt‰ osallistujien nimet.
4. Ohjelma arpoo osallistujat vastakkain ensimm‰iselle kierrokselle. 
4.1 Jos pelaajia on pariton m‰‰r‰, ohjelma antaa yhdelle BYEn.
4.2 Jos pelaajia on ep‰sopiva m‰‰r‰ KO-taulukkoon (bin‰‰rinen potenssi), tyhj‰t kohdat t‰ytet‰‰n BYEill‰ turnauksen kannalta j‰rkev‰ll‰ tavalla, eli BYEt jaetaan eri puolille kaaviota niin tasaisesti kuin mahdollista.
5. Ottelutulosten lis‰‰minen. V‰hint‰‰n voittajan merkint‰ kuhunkin otteluun. Voidaan laajentaa jonkinlaiseen pisteytysj‰rjesatelm‰‰n.
6. Kun kaikki kierroksen ottelutulokset on lis‰tty, kierros p‰‰ttyy. Kierroksen p‰‰tteeksi ohjelma kysyy, onko joku edelleen turnauksessa mukana olevista pelaajista p‰‰tt‰nyt l‰hte‰ turnauksesta kesken. Jos on, n‰m‰ tulee poistaa ennen kuin seuraava kierros alkaa.
7. Jos Swiss tai vastaava, ohjelma generoi seuraavan kierroksen vastustajat. Jos KO tai vastaava, t‰m‰ kohta hyp‰t‰‰n yli.
8. Ottelutulokset jne.
9. Jatketaan kunnes turnaus loppuu ja voittaja(t) on saatu selville.

Laajennettavuutta:
Visuaalinen KO -turnauskaavio, johon pelaajat sijoittuvat
Swiss -turnausmuoto
Tasapelien mahdollisuus ja k‰sittely
Turnauksen tilanteen (turnauskaavion) tarkastelu turnauksen ollessa k‰ynniss‰ esim. internetitse
VAIHTOEHTONA edelliseen: kierrosten v‰lill‰ exportattava turnauskaavio, esim. JPG tai PNG -muodossa. Johon mahdollisesti automaattinen upload-mahdollisuus.
J‰ljell‰ olevaa kierrosaikaa (= pelaajien peliaikaa) laskeva countdown-kello, jota voi halutessaan k‰ytt‰‰ mutta ei ole pakko. S‰‰dett‰v‰ kierrosajan pituus.
