---
marp: true
paginate: true
theme: uncover  
style: |
  /*Til hele sliden*/
  section {
    background-color: #fefefe;
    font-family: -apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial,Noto Sans,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji;
    animation: marp-transition-fade 1.9s;
  }
  section::before{
    content: "";
    display: block;
    position: absolute;
    left: 0;
    top:0;
    width: 100%;
    height: 150%;
    animation: marp-transition-explosion 1.8s;
  }
  /*Slide animation*/
  @keyframes marp-transition-explosion {
    from {
        left: -700px;
        background: url("https://i.gifer.com/origin/40/408fefc1a632831d9b390464afc8b944_w200.gif") left no-repeat, url("https://i.gifer.com/origin/40/408fefc1a632831d9b390464afc8b944_w200.gif") right no-repeat, url("https://acegif.com/wp-content/uploads/gif-explosion-11.gif") center/100%;
        background-color: white;
    }
    to {
        left: 0px;
        background: url("https://i.gifer.com/origin/40/408fefc1a632831d9b390464afc8b944_w200.gif") left no-repeat, url("https://i.gifer.com/origin/40/408fefc1a632831d9b390464afc8b944_w200.gif") right no-repeat, url("https://acegif.com/wp-content/uploads/gif-explosion-11.gif") center/100%;
        background-color: white;
    }
  }
  @keyframes marp-transition-fade{
      from{
          transform: rotate(0deg) scale(0);
          left: -700px;
          color: white;
      }
      to{
          transform: rotate(360deg) scale(1);
          left: 0px;
          color: black;
      }
  }
  /*Til headers (H1)*/
  h1 {
    font-weight: 700;
  }
  /*Til texten indeni (eller H2)*/
  h2 {
    font-weight: 400;
  }
  /*Til pagination*/
  section::after {
      content: attr(data-marpit-pagination) ' / ' attr(data-marpit-pagination-total);
      display: block;
      background-color: #333;
      color: #aaaaaa;
      border-top-left-radius: 10px;
      height: 40px;
      min-width: 100px;
      padding: 4px;
      text-shadow: none;
      text-align: center;
  }

---
![bg left:33%](https://media.istockphoto.com/photos/project-management-concept-chart-with-keywords-and-icons-the-meeting-picture-id894203302)
# Project Management
- Sofus
- Allan
- Joachim
- Casper
---
![bg right:33%](https://miro.medium.com/max/1400/1*qnbRKYQIx96TWcI8ZPfa2g.jpeg)
# Project Board
- Senior User
- Project Executive
- Senior Supplier
<!-- Project boardet best??r af tre roller:
 - Senior User
 - Project Executive
 - Senior Supplier
Flere personer kan v??re under Senior rollerne, men kun ??n kan v??re Project Executive, og nogle gange er det CEO. -->
---
# Senior User
![bg left:33%](https://media.discordapp.net/attachments/761110319707062287/978911051783491664/Sixty-and-Me_Stevie-Wonder-Birthday.jpg?width=657&height=657)

- Stevie Wonder
- 72 ??r gammel
- Menneskekender 
- Mange samarbejdsprojekter
---
# Stevie Wonder
- Ansvarlig for at slut brugernes behov bliver opfyldt
- De mange forkellige typer af mennesker Stevie har arbejdet sammen med over en lang periode giver ham de n??dvendige kompetencer
<!--  Ansvarlig for at slut brugernes behov bliver opfyldt b??de i form af funktionalitet og user experience.
Generelt kvaliteten af oplevelsen af d??t produkt der bliver leveret. -->
---
# Project Executive
![bg right:33%](https://media.discordapp.net/attachments/761110319707062287/978913185279139840/johnny-depp-1-2000.webp?width=657&height=657)
- Jacob "Johnny Depp" Enevoldsen Duus
- 58 ??r gammel
- Stifter af Infinitum Nihil
- Producer p?? flere projekter
---
# Jacob "Johnny Depp" Enevoldsen Duus
- En realistisk person med selvkontrollen og erfaringen til at stoppe n??r projektet er f??rdigt
- Gennem de mange projekter Hr. Depp har v??ret med, giver ham indblik p?? projektstart og drift af projekter
<!-- Han har ogs?? haft en kone der sked p?? hans seng. -->
---
# Senior Supplier
![bg left:33%](https://cdn.discordapp.com/attachments/761110319707062287/978911116417724416/jason-statham-attends-the-press-conference-of-director-f-gary-grays-film-the-fate-of-the-furious-on-march-23-2017-in-beijing-china-photo-by-vcg_vcg-via-getty-images-square.jpg)
- Jason Statham
- 54 ??r gammel
- Mekaniker
- Tidligere medlem af Britanniens nationale sv??mme trup
---
# Jason Statham
- En som kan finde de rette l??sninger til interne problemstillinger, n??r det g??lder hardware eller v??rkt??j
- S??rger for de rigtige resourcer og kvaliteten af de resourcer
<!-- De rigtige resourcer kan v??re:
- v??rkt??jer
- r??materialer
- arbejdskraft
- hardware
Derudover s??rger han ogs?? for at f??rn??vnte er af den n??dvendige kvalitet. -->
---
# Project Manager
![bg right:33%](https://cdn.discordapp.com/attachments/761110319707062287/978916188279164998/Screenshot_from_2022-05-25_09-02-29.png)
- Billy Ray Cyrus
- 60 ??r gammel
- Country synger og skuespiller
- Far til Miley Cyrus
---
# Billy Ray Cyrus
- St??r for den daglige drift/management af projektet p?? vegne af Project Boardet
- Er konstant i dialog med personerne p?? Project Boardet, samt holdet p?? Project Assurance og Team Managers
<!-- S??rger for at kommunikere de rigtige data til Project Boardet, nogle gange i samhold med Project Assurance, for at s??rge for at dataen er korrekt. -->
---
# Change Authority
![bg left:33%](https://media.discordapp.net/attachments/761110319707062287/978943537762668574/5f8748842afdc6bcfb6489d3faca171f.jpg)
- Dolly Rebecca Parton
- 76 ??r gammel
- Medejer af The Dollywood Company
- Tidligere medejer af Sandollar Productions
---
# Dolly Rebecca Parton
- En der kan h??ndtere ansvaret for beslutninger og hj??lper med at styre flowet af projektet
- Med sine erfaringer som medejer af firmaer som holder flere virksomheder, kan hun tage ansvaret og beslutninger som kunne forekomme
<!-- Denne rolle kan ogs?? tilegnet Project Manageren, hvis Project Boardet tillader det.
Sidder med ansvaret for de lidt mindre ??ndringer, hvor Project Boardet st??r for de helt store.
??ndringerne g??res hvis det giver mening og kan g??res indenfor deadline og budget. -->
---
# Project Assurance
![bg right:33%](https://cdn.discordapp.com/attachments/761110319707062287/978919012597628938/Screenshot-2020-08-18-at-11.13.41.webp)
- Miley Cyrus
- 29 ??r gammel
- Billy's datter
- Assisteret med p?? flere projekter
---
# Miley Cyrus
- En person der kan have sin egen holdning og forst??else af den information som kommer l??ngere op i strukturen
- Miley Cyrus blev talskvinde for "Daisy Rock Guitars" i 2004
- Disney udgav en Hannah Montana-t??jkollektion sidst i sommeren 2007. Miley Cyrus hjalp med at designe t??jet til kollektionen
<!-- Denne rolle st??r for at de korrekte data kommer op til Project Boardet. Dette kan g??res i samhold med Project Manageren og Team Managers.
Team Managers kan tr??kke i Project Assurance, hvis de har mistanke om at Project Manageren giver de forkerte data til Project Boardet. -->
---
![bg left:33%](https://sm.ign.com/ign_dk/screenshot/r/reef-kober-licensen-til-terminator/reef-kober-licensen-til-terminator_7w4m.jpg)
# Projekt Terminering
- Hvis produktet ikke l??ngere er brugbart
- Hvis suplier ikke kan levere n??dvendige dele
- Hvis firmaet som ??nsker produktet g??r konkurs 
- Hvis produktets v??rdi ikke l??ngere udvejer prisen
<!--
Projektet kan termineres hvis f.eks...
- Hvis produktet ikke l??ngere er brugbart, f.eks.:
  - Det har taget for lang tid
  - Budgetet er ikke overholdt
- Hvis suplier ikke kan levere n??dvendige dele, f.eks.:
  - De rigtige mennesker
  - De rigtige v??rkt??jer
  - De rigtige (r??)materialer
- Hvis firmaet som ??nsker produktet g??r konkurs
- Hvis produktets v??rdi ikke l??ngere udvejer prisen
-->
---
![bg right:33%](https://thumbs.dreamstime.com/b/broken-stone-close-up-top-view-horizontal-photo-broken-stone-close-up-top-view-horizontal-photo-218862972.jpg)
# Hvilke dokumenter er ???make-or-break??? for projektet?
<!-- Her er der tale om de vigtigste dokumenter, s?? som Project Initiation og Business Case -->
---
![bg left:33%](https://media.discordapp.net/attachments/904869617888018442/980806650061545502/Screenshot_from_2022-05-30_14-08-44.png?width=374&height=657)
### Project initiation documentation
- Indeholder "approaches" til forskellige dele af PRINCE2
- Planer og Definering af projektet
- Business case
<!-- Dette skal v??re det f??rste dokument, der forklarer projektet, og hvordan det skal startes. Denne indeholder tilgange til de forskellige dele af PRINCE2, planer samt definition af projektet, og projektets start-business case. -->
---
![bg right:33%](https://ak.picdn.net/offset/photos/57fe53c0ba6f6bfc1a493800/medium/photo.jpg)
### Business case
- Udforming af projektet fra en ??konomisk vinkel
- Finansielle aspekter der g??r projektet ??konomiske levedygtigt
<!-- Dette dokument skal helst ??ndre sig som projektet k??rer der ud af.
Det er et "levende dokument", ligesom projektet er "levende".
Hvis budgettet ??ndrer sig, eller der er andre ??ndringer eller tilf??jelser, s??ttes korresponderende data ind i business casen. -->
---
![bg left:33%](https://m.media-amazon.com/images/M/MV5BMTk2MDU2MzgzNl5BMl5BanBnXkFtZTgwNTY1MzY0MjE@._V1_.jpg)
# Hvilke faktorer er ???make-or-break??? for projektet? 
<!-- De 7 principper for et Prince2 projekt -->
---
![bg right:33%](https://media.istockphoto.com/photos/start-button-picture-id545464260)
### Opstart
- Hvis man ikke kan pr??ssentere planen for projektet, give plantegning over produktet og give nogle klare beskrivelser af business casen, vil projektet aldrig blive startet op
<!-- Det er vigtigt at kunne fremvise projektplanen, med klare rolledeligeringer klare beskrivelser af business casen.
Der skal v??re lagt et budget, aftalt hvem sidder hvor, og hvem g??r hvad. Derudover skal plan og resourcer v??re p?? plads med f.eks.:
- Plantegninger
- OwO wats dis?!
- Resourcer
  - Mennesker
  - V??rkt??jer
  - Evt. viden
  - osv -->
---
![bg left:33%](https://www.wikihow.com/images/thumb/e/e9/Improve-Eye-Hand-Coordination-Step-13.jpg/aid1378324-v4-1200px-Improve-Eye-Hand-Coordination-Step-13.jpg)
### Koordinering
- Projektkomit??en v??lger om gruppen skal forts??tte ud fra den g??ldende projektplan og kan lave ??ndringer i forehold til at holde resourcer og tid under kontrol 
<!-- L??s slide. kek -->
---
![bg right:33%](https://thumbs.dreamstime.com/b/words-story-begins-notepad-close-up-words-story-begins-notepad-close-up-210993596.jpg)
### Igangs??ttelse
- Projektkomit??en v??lger en projekt leder og laver en meget grundig projektplan. Dette inkluderer tid, kvalitet, muligheder og profit
- Projektet kan g?? i gang s?? snart projektkomit??en giver fuld accept
<!-- Det er her projektet oprigtigt starter. -->
---
![bg left:33%](https://s1.gaming-cdn.com/images/products/7467/orig-fallback-v1/control-ultimate-edition-ultimate-edition-pc-spil-steam-europe-cover.jpg)
### Kontrollering
- I denne fase uddeler projektvejlederen arbejdet ud i mindre dele, som bliver uddeligeret til forskellige teams
<!-- Scrum eller lignende kan bruges til programm??rerne.
Andet kender vi ikke lige umiddelbart til, det m?? infrastruktur tilf??je.
Men opgaverne bliver uddeligeret s?? det passe til de forskellige hold, s?? som netv??rkfolk f??r netv??rksrelaterede opgaver osv. Senior Supplier skal umiddelbart v??re den der s??rger for dette. -->
---
![bg right:33%](https://www.insightssuccess.com/wp-content/uploads/2021/02/2-55.jpg)
### Overv??gning af produktlevering
- Projekt administratoren laver kvalitets tjek og v??lger om der skal arbejdes mere p?? produktet
<!-- Dette sker f??r vi udlevere produktet, og hvor vi laver kvalitetscheck af hvordan produktet er nu, og vurderer om det er ok eller om vi skal arbejde yderigere p?? det.
Egentlig skulle man ogs?? s??rge for at lave kvalitetschecks "on the go". -->
---
![bg left:33%](https://cdn.prgloo.com/media/fa81802b752f466593ce67947dba0e63.jpg?width=580&height=870)
### Overv??gning af fasegr??nser
- Ved afsluningen af hver fase holder projektbestyrelsen (project board) en audit og vurderer om projektet skal forts??tte eller afsluttes
<!-- Denne audit er baseret p?? hvad Project Manager og Project Assurance melder til toppen. Tyder dataen p?? noget godt, forts??tter vi, hvis ikke, kan det vurderes at projektet skal termineres. -->
---
![bg right:33%](https://f8n-ipfs-production.imgix.net/QmaangUFNxGD6vRjnqzVnL2DaFgx4QX38F2LkxZY8WJqkK/nft.jpg?q=80&auto=format%2Ccompress&cs=srgb&h=640)
### F??rdigg??relse
- F??r projektet afsluttes f??rdig??re projektlederen det sidste papirarbejde, udleveringer og detaljer
<!-- Dette kan umiddelbart ogs?? ske i samhold med overv??gning af produktleveringen, hvor der bliver kvalitetschecket osv. -->
---
![bg left:20%](https://media.discordapp.net/attachments/761110319707062287/978913185279139840/johnny-depp-1-2000.webp?width=657&height=657)
# Hvilke roller har autoriteten til at terminere projektet?
- Project Executive er den ultimativt ansvarlige person for hele projektet med et erhvervsm??ssigt mindset. De st??r for at terminere eller aflsutte projektet
<!-- Det er Project Executive der er den ultimateive rolle der kan terminere eller v??lge at forts??tte projektet.
Dette g??res dog typisk i sammarbejde med Project Boardet, hvor der kan blive efterspurgt hvordan projektet g??r. -->
