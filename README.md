## Udemy Course: "Complete Blender Creator: 3D Modelling"

Instructor: Grant Abbit

https://www.udemy.com/course/blendertutorial/?couponCode=26BBPAA2MX

## Summary

Et begynderkursus for Blender, som er et tool til at lave 3D modeller.

## Table of Contents

[TOC]

## Section 1: Introduction & Setup

### Community & Support

Der er et community ved navn GameDev.tv, som f.eks. kan tilgås på Discord og Facebook

### Navigation

***Øv dig gerne i det her jævnligt, så du får det ind på muskelhukommelsen.***

Der er mange paneler, f.eks. outline (øverst til højre), properties (nederst til højre) og viewport (det store i midten).

Tryk og drag middle mouse button (rullehjulet) for at **rotere kameraet** omkring det aktuelle center point (ikke at forveksle med "3d-cursoren", der ligner en redningskrans).

**Strafe** (hvor synsretning bibeholdes, men man flytter sig) med SHIFT + Tryk og drag middle mouse button. Det svarer til at klikke på det lille hånd-ikon og så dragge rundt.

**Zoom ind og ud** med musehjulet. svarer til at klikke på det lille forstørrelsesglas-ikon og så dragge rundt.

Man kan køre ***smooth* zooming** ved med CTRL+ click and drag med middle mouse button.

Med **numpadden** (dvs knapperne til højre på keyboardet) kan man hurtigt placere kameraet, så det kigger langs z-aksen osv:

1: Front view

CTRL+1: Back view (langs y-aksen)

3: Side view

CTRL+3: Other side view

7: Top view 

CTRL+7: Bottom view 

Bemærk, at det skifter fra perspective view til orthographic/isometric view. det fremgår også af det lille ikon ved siden af hånden og forstørrelsesglasset. Man kan også skifte arbitrært mellem perspective view og orthographic/isometric view ved at klikke på det ikon.

Bemærk også, at man kan klikke på boldene i det røde/grønne/blå koordinatsystem øverst til højre i viewet som alternativ til at bruge numpadden.

Man kan også rotere viewet arbitrært ved at klikke og dragge på den grå cirkel, der fremkommer ved at hovere musen over det rød/grønne/blå koordinatsystem.

Bemærk, at enhederne på akserne faktisk er i METER, og at den der kube, man har fra starten, er 2 meter på alle leder!

Vælg noget ved at klikke på det - så får det en orange kant.

Hvis man klikker på *kamera*-ikonet ved siden af hånd-ikonet, toggler man til det view, som kameraet har. Det bruges til at rendere "the final image", hvilket er nyttigt til at publicere sit værk. Man kan gøre det samme ved at trykke 0 på numpadden.

### Adding Objects

Klik på add i viewportens menu og vælg Mesh -> Plane. Så laves en plade med centrum i 3D cursoren  ("redningskransen").

Det er i øvrigt bedre at åbne Add menuen med shortcuttet SHIFT+A.

Flyt 3D cursor med SHIFT+right click. Den afgør f.eks. hvor nye objekter placeres. Klikker man på et 3D-objekt placeres 3D cursoren på objektet. Hvis man derimod klikker i det fri, placeres den på en plan, der går gennem fokus punktet for viewport (det, man roterer omkring) og som er vinkelret på synsretningen.

SHIFT+S åbner "3D cursor menuen", som f.eks. kan bruges til at sende 3D cursoren tilbage til "world origin" (origo).

Man kan selecte objekter ved at klikke på dem og evt bruge SHIFT for at udvide selection. Alternativt kan man bruge outline viewet til at selecte. Man kan i øvrigt selecte ved at dragge et vindue - både i viewport og i outline. Man kan tilsyneladende ikke bruge CTRL+click til at fjerne objekter fra sin selection.

Bemærk, at der også er et light i scenen, so også kan ses i outline viewet.

I en selection er der ét objekt, der er gult, mens de resterende er orange. Det gule objekt er det "aktive" objekt.

Slet en selection af 3D objekter ved at trykke på delete knappen.

Tryk på knappen T for at toggle om "tools panel" er synligt.

**Flyt** (translater) objekter ved at klikke på Move-knappen i tools panel, selecte et antal objekter, og dragge i de røde/grønne/blå pile i det koordinatsystem, der fremkommer ved selectionen. Bemærk, at der også er nogle små plader, hvor man kan låse en akse men ellers flytte objekterne frit.

**Roter** objekter med Rotate knappen i tools panel. Den minder om flyt og er meget intuitiv - man kan rotere om en af de 3 akser eller rotere frit.

**Skaler** objekter med Scale knappen i tools panel. Den minder også om flyt og rotate og er meget intuitiv. Bemærk, at man ligesom med Rotate skal klikke ved siden af kontrollerne for at skalere hele 3D objektet frit.

De er også en generel **Transform** knap i tools panelet, so sådan set bare er alle de foregående samlet i ét tool.

SHIFT+Spacebar åbner tool menu.

S-knappen er direkte shortcut til Scale (virker på den aktuelle selection af 3D objekter)

R-knappen er direkte shortcut til Rotate (virker på den aktuelle selection af 3D objekter)

G-knappen er direkte shortcut til "Grabbing og movement" (virker på den aktuelle selection af 3D objekter, og når man flytter rundt på selection, bibeholder 3D objekterne deres afstand til kameraet). Når man er i grab mode efter at have trykket på G-knappen, kan man f.eks trykke på X-knappen for at constraine movement til at være langs X-aksen. Hvis man derimod trykker SHIFT+X restrictes movement således at objektet låses til sin nuværende position på X-aksen men kan flyttes frit rundt i dets nuværende Y/Z-plan. Det samme gælder for tryk på Y, SHIFT+Y, Z og SHIFT+Z.

For finjusteringer kan man åbne menuen til højre for det lille blå/røde/grønne koordinatsystem og justere koordinaterne for et det aktive objekt direkte. Hvis man vil sætte en koordinat, f.eks. Y-koordinaten til det samme for alle objekter i sin selection, kan man holde ALT nede, når man klikker på et felt. Når man så indtaster en koordinat og trykker enter, får alle objekter i selectionen sat koordinaten til den pågældende værdi. Menuen kan skjules ved at trække dens venstre kant ind til højre igen. Man kan også toggle, om den vises, ved at trykke på N-knappen.

Shift+klik på et objekt tilføjer et objekt til ens selection, og det kan også bruges til at gøre et objekt til det aktive objekt.

Når man roterer, kan man også *indtaste* rotationsvinklen i stedet for at dragge med musen. Man kan f.eks. selecte et objekt og så trykke R (rotate), X (omkring x-aksen) og "90" + enter for at dreje et objekt 90 grader omkring x-aksen.

Undo: CTRL+Z

Redo: CTRL+SHIFT+Z

### Viewport & Rendering

Over det røde/grønne/blå koordinatsystem er der en horisontal toolbar, der styrer, hvordan scenen renderes. Som default er "Viewport shading" sat til "solid", men man kan skifte til f.eks. wireframe. For begge modes kan man slå "X-ray" mode til eller fra - det afgør, om objekterne bliver gennemsigtige, hvilket kan være hensigtsmæssigt, hvis de overlapper hinanden.
Der er også et mode, der hedder "Material preview", der giver en flot belysning. Bemærk, at det pr default *ikke* afhænger af det "lys"-objekt, der pr default er med i scenen lige som kameraet. For at få lyseffekter med fra lys i scenen, skal man sætte viewport shading til "rendered" ved at trykke på knappen til højre for material previewknappen i toolbaren øverst til højre.

Man kan skifte til et andet workspace kaldet "shading workspace" (fra default work spacet "layout") ved at trykke på "Layout" knappen i hovedmenuen. Bemærk, at der fremkommer 2 kugler i bunden. Den til højre repræsenterer et såkaldt HDRi, som står for High Dynamic Range image. HDRi vises også som den flerfarvede bagrund i viewport og giver en flot, ambient, realistisk belysning af scenen.

Man kan konfigurere workspacet ved at trykke på elementet længst til venstre i toolbaren i viewet under viewporten (pr default er den sat til "Shader editor"). Workspacet består også af en "image editor" nederst til venstre (kan bruges til at putte tekstur på 3D objekter) og en "file browser" øverst til venstre (til at dragge filer ind i shader editor). Outline panelet og property panelet er stadig med i shading workspace, lige som de var i layout workspace.

Bemærk, at HDRi'en pr default ikke er med, når man sætter viewport shading til rendered.

Bemærk, at man kan gøre objekter usynlige ved at trykke på ikonerne til højre for dem i outline panelet øverst til højre. Øje-ikonet gør dem usunlige i viewporten, mens kamera-ikonet gør dem usynlige i det billede, som man kan generere under anvendelse af kameraets synsvinkel.

Man kan ændre kameraets position ved at gå ind i kameraview (trykke 0 på numpadden) og så trykke på lås-ikonet tæt på hånden. Når man så manøvrerer rundt i viewporten, som man normalt gør, følger kameraet med.

Man kan generere et renderet billede ved at klikke på Render-knappen til venstre i hovedmenuen. Så popper et vindue op med det renderede image, hvor man så f.eks. kan trykke save image. Det renderede billede er som regel lidt pænere end hvad man ser i viewporten, fordi den beregner lyseffekter osv fuldt ud. Man kan styre, hvordan billedet renderes i viewporten ved f.eks. at skifte render engine fra "EEVEE" til "cycles" (som er en ray tracing engine) i properties panelet. Man kan også konfigurere, om den skal bruge CPU'en eller GPU'en til at rendere i viewporten. Generelt er det hurtigst at bruge GPU'en.

### Material Colours

Skift til "Shading" workspacet, og sikr, at du har sat viewport shading til "rendered". Klik på et 3D objekt i viewporten og klik så på den grå "New"-knap i Shader editor panelet under viewporten for at lave et nyt material til objektet. Bemærk, at kuben, som var der fra starten, allerede har et material. Man panorerer og zoomer i shader editoren på samme måde som i viewporten, dvs zoom med musens rulle hjul og panorer med click og drag med rullehjulet. Klik på "base color" feltet og vælg en farve i color dialogen. Nye materials tildeles et navn, som man kan ændre arbitrært. Et material kan genbruges, så i stedet for at lave et nyt material til et objekt kan man også klikke på et objekt og tildele det et *eksisterende* material ved at klikke på den grå drop down knap til venstre for New-knappen.

Man kan bruge Render Engine: EEVEE sammen med Ray tracing for at gøre det lidt pænere, men der er stadig ikke lige så pænt som at sætte Render Enginge til Cycles.

### Material Reflections

Udover farve kan man for et material sætte egenskaberne: Metallic, Roughness, IOR og Alpha. Man kan også klikke på et objekt og vælge "Object" i viewportens toolbar, hvor man så kan vælge shade smooth for at justere, hvordan materialet ser ud for det pågældende objekt. Det påvirker så kun det ene objekt. Shade smooth virker ikke så godt på objekter med en skarp kant såsom en cylinder, men så kan man bruge Shade autosmooth i stedet. Man kan i øvrigt højreklikke på objekterne for at få menuen frem som en context menu.

Man kan gå til et site, der hedder "Poly Haven" for at hente en HDRi til sin scene for at lave en flot lyseffekt (det gik jeg lidt hurtigt henover). Han demonstrerer også, hvordan man kan tweeke sin rendering, så man kan trade kvalitet for processeringstid.

### Lighting

Han viser, hvordan man kan ændre egenskaberne for sine lysobjekter for at ændre beslysning i sin side. Pr default er et lys et point light, men man kan skifte til sun, spot eller area og justere styrke, farve osv.

Man kan i øvrigt trykke SHIFT+D for at duplikere et objekt.

### Editing objects

Skift fra "Object mode" til "Edit mode" ved at klikke i venstre side af viewportens toolbar. Edit mode er pr. default "vertex mode", hvor man kan flytte rundt på en selection af vertices med den sædvanlig metode, hvor man trykker på G og dragger rundt. Man kan også skifte til "Edge mode" eller "Facet mode". Det minder meget om at flytte, rotere eller skalere et helt objekt - her gør man det bare med en selection af vertices, edges eller facets. Man kan skifte mellem de 3 modes ved at trykke på tasterne 1, 2 og 3. På denne måde ændrer man ikke på antallet af vertices, edges og facets, men det kan man gøre ved f.eks. at gå i facet mode, vælge en facet og så trykker på tasten "E" og så dragge. Der er også et "Loop cut" tool med shortcut CTRL+R, som kan bruges til at lave et "snit" gennem figuren for at lave flere facets uden at ændre objektet.

Tryk i øvrigt på "T"-tasten toggler, om toolbaren er synlig.

### Simple Houses

Små øvelser i at lave simple figurer.

Tryg TAB for at skifte mellem Object Mode og Edit Mode. Generelt tager TAB en hen til det forrige mode.

Bemærk, at hvis man tilføjer et nyt mesh i Edit mode, bliver det en del af det aktive objekt. Hvis man kommer til at gøre det ved en fejl, kan man gå ind i Edit mode, klikke P og vælge "Separate, by loose parts" for at skille meshes ad.

### Making a Lighthouse

Man kan ændre navne på sine objekter i "Outline" panelet eller ved at trykke F2 efter at have valgt et objekt i viewporten.

Man kan skjule en masse objekter hurtigt ved at klikke og dragge på øje-ikonerne i Outline panelet.

Man kan lave en collection ved at klikke på det lille ikon med et plus i øverste højre hjørne af "Outline"-panelet. Man kan også gøre det ved at trykke på M-tasten. Hvis man har valgt et antal objekter, bliver de en del af den nye collection.

Man kan flytte objekter mellem collections som hvis det var filer i Explorer.

Collections kan navngives og skjules lige som objekter.

Bemærk, at når man tilføjer f.eks. en cylinder, popper der en lille "Add Cylinder"-dialog op i nederste venstre hjørne af viewporten. Her kan man ændre på antal facets osv. Han anbefaler i øvrigt at arbejde med så få facets som muligt og siger, at man let kan øge antallet af facets, mens det er sværere at gå den anden vej og reducere antallet af facets.

Han viser en smart variant af det at extrude, hvor han går i Edit mode, vælger facet mode, selecter en facet og trykker E for at ekstrudere, men FØR han flytter musen trykker han så S for at skalere - i det her tilfælde for at gøre den lidt mindre.

Han viser også det såkaldte "Inset" tool, som en en art sammensætning af extrude og scale, hvor man klikker på en polygon og trykker "I" for at lave en ny, hænger sammen med den selectede, men som er mindre.

Når man skalerer noget, kan man intaste skala, f.eks. 0, hvis noget skal kollapses helt. Det demonstrerer han med toppen af fyrtårnet.

Han viser en smart måde at selecte mange polygoner på én gang, hvor man holder ALT nede og klikker på en edge. Så selecter den alle de *facets*, der "hænger sammen" omkring den selectede edge. Det kan man f.eks. bruge til at justere sin figur.

### Making the Rocky Base

Denne lektion handler om **sculpting**. Lav en plane og rumlig figur såsom en icosphere, og aktiver "Sculpting" workspace. Her har man et antal "brush" tools til at deformere objekter. Bemærk, at sculpt kun virker på det *aktive* objekt og altså ikke på andre selectede objekter (mørkeorange omrids).

Pr default er "Draw" brush toolet aktivt - det "bygger" på meshet. Tryk på F for at ændre brush size og SHIFT+F for at ændre brush strength. Man bruger den ved at klikke og dragge rundt på sit objekt - toolet trækker så facets *udad*, der hvor den er. Bemærk, at der ikke ændres på antallet af facets - det kan man til gengæld gøre med "DynTopo" eller "Remesh", som er i højre side af toolbaren over viewporten i Sculpt workspacet. Bemærk, at DynTopo er en checkbox. Det minder om det simple sculpting tool, men tilføjer facets, så ens objekt bliver mere smooth. Man kan tune DynTopo toolet ved at klikke på drop down pilen. Så kan man f.eks. sætte detailing til constant (så den ikke afhænger af zoom level). Man kan også ændre "Resolution" til en anden værdi for at påvirke, hvor store nye meshes skal være.

Holder man CTRL nede, *skubber* man til facets i stedet for at trække i dem.

Holder man SHIFT nede, smoother man meshet med toolet, så facets i højere grad gøres ensartede i størrelse og får mindre vinkler mellem sig. Det virker uanset hvilken brush, der er aktiv.

Man kan dragge den nederste toolbar med brushes op for at se alle de mange brushes, man kan bruge. De brushes, der har noget gult på deres knap, er kendetegnet ved at de ikke ændrer antallet af facets - så de er ikke påvirket af Dyntopo.

Han demonstrerer "Grab brush", der trækker/skubber vertices.

### The Decimate Modifier

Det er en metode til at reducere antallet af facets. Skift til Layout workspace, vælg et objekt, klik på wrench ikonet i properties panelet, klik på Add modifier-knappen og frag så i "Ratio"-slideren (som ligner en knap). Bemærk, at modifieren forbliver en egenskab ved objektet, så man f.eks. kan gå tilbage mod flere facets, hvis man vil. Man kan også skjule modifierens effekt ved at klikke på skærm-ikonet til højre for den valgte modifier i properties panelet. Man kan også stakke flere modifiers oven på hinanden. Bemærk, at man ikke kan ændre på modifierens output med f.eks. sculpt toolet. Hvis man vil gøre det, skal man "applye" sine modifers ved at klikke på drop down pilen til højre for den valgte modifier i property panelet. Så er der til gengæld ikke nogen vej tilbage til det originale mesh. Det er derfor som regel noget man gør i forbindelse med at færdiggøre sin model.

Så demonstrerer han "Proportionate Editing" tool, som man kan aktivere ved at klikke på en knap i midten af toolbaren over viewporten i Edit mode (eller med shortcut O). Den ændrer adfærden af grab (G) og move af vertices, edges eller facets, så det f.eks. ikke kun er *individuelle* vertices, der påvirkes, men også dem i nærheden - afhængigt af, hvilken indstilling, man har valgt for Proportionate Editing (smooth, linear, osv). Man kan også ændre radius på "circle of influence", ved at bruge musens rullehjul.

### Snapping

## Tips, jeg selv har fundet ud af, bl.a. med hjælp fra ChatGpt

### Flytte Origin for et objekt

Origin er en lille orange dot, der knytter sig hvert 3D objekt og afgør, hvordan den skaleres osv. Det kan være nødvendigt at flytte den, hvilket f.eks. kan gøres ved at højreklikke på det aktive objekt i Layout workspace og så vælge "Set Origin" og så vælge blandt mulighederne der.

### Joine et antal objekter

Hvis man f.eks. har lavet en bil ved at lave en kube og 4 torusser, så kan man lave det om til ét objekt ved at selecte alle objekter, højreklikke og vælge Join. Bemærk at Origin fra det *aktive* objekt bruges som origin for det nye joinede objekt.

### Eksportere udvalgte objekter til stl
Klik på kamera-ikonet ud for de objekter i Outline panelet øverst til højre, for at styre, hvilke der skal med i output. Det er helt ækvivalent til, hvordan man styrer, om de skal med i et renderet billede.
