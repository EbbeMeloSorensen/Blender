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

Man kan selecte objekter ved at klikke på dem og evt bruge SHIFT og CTRL. Alternativt kan man bruge outline viewet til at selecte. Man kan i øvrigt selecte ved at dragge et vindue - både i viewport og i outline.

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



