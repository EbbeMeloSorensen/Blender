## Udemy Course: ""

Instructor: Grant Abbit

https://www.udemy.com/course/blendertutorial/?couponCode=26BBPAA2MX

## Summary

Et begynderkursus for Blender, som er et tool til at lave 3D modeller.

## Table of Contents

[TOC]

### Section 1: Introduction & Setup

#### Community & Support

Der er et community ved navn GameDev.tv, som f.eks. kan tilgås på Discord og Facebook

#### Navigation

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

#### Adding Objects

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

#### Viewport & Rendering

Over det røde/grønne/blå koordinatsystem er der en horisontal toolbar, der styrer, hvordan scenen renderes. Som default er "Viewport shading" sat til "solid", men man kan skifte til f.eks. wireframe. For begge modes kan man slå "X-ray" mode til eller fra - det afgør, om objekterne bliver gennemsigtige, hvilket kan være hensigtsmæssigt, hvis de overlapper hinanden.
Der er også et mode, der hedder "Material preview", der giver en flot belysning. Bemærk, at det pr default *ikke* afhænger af det "lys"-objekt, der pr default er med i scenen lige som kameraet. For at få lyseffekter med fra lys i scenen, skal man sætte viewport shading til "rendered" ved at trykke på knappen til højre for material previewknappen i toolbaren øverst til højre.

Man kan skifte til et andet workspace kaldet "shading workspace" (fra default work spacet "layout") ved at trykke på "Layout" knappen i hovedmenuen. Bemærk, at der fremkommer 2 kugler i bunden. Den til højre repræsenterer et såkaldt HDRi, som står for High Dynamic Range image. HDRi vises også som den flerfarvede bagrund i viewport og giver en flot, ambient, realistisk belysning af scenen.

Man kan konfigurere workspacet ved at trykke på elementet længst til venstre i toolbaren i viewet under viewporten (pr default er den sat til "Shader editor"). Workspacet består også af en "image editor" nederst til venstre (kan bruges til at putte tekstur på 3D objekter) og en "file browser" øverst til venstre (til at dragge filer ind i shader editor). Outline panelet og property panelet er stadig med i shading workspace, lige som de var i layout workspace.

Bemærk, at HDRi'en pr default ikke er med, når man sætter viewport shading til rendered.

Bemærk, at man kan gøre objekter usynlige ved at trykke på ikonerne til højre for dem i outline panelet øverst til højre. Øje-ikonet gør dem usunlige i viewporten, mens kamera-ikonet gør dem usynlige i det billede, som man kan generere under anvendelse af kameraets synsvinkel.

Man kan ændre kameraets position ved at gå ind i kameraview (trykke 0 på numpadden) og så trykke på lås-ikonet tæt på hånden. Når man så manøvrerer rundt i viewporten, som man normalt gør, følger kameraet med.

Man kan generere et renderet billede ved at klikke på Render-knappen til venstre i hovedmenuen. Så popper et vindue op med det renderede image, hvor man så f.eks. kan trykke save image. Det renderede billede er som regel lidt pænere end hvad man ser i viewporten, fordi den beregner lyseffekter osv fuldt ud. Man kan styre, hvordan billedet renderes i viewporten ved f.eks. at skifte render engine fra "EEVEE" til "cycles" (som er en ray tracing engine) i properties panelet. Man kan også konfigurere, om den skal bruge CPU'en eller GPU'en til at rendere i viewporten. Generelt er det hurtigst at bruge GPU'en.

#### Material Colours

..







